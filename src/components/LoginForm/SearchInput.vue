<script setup>
</script>

<template>
    <div class="phone-container">
        <div class="phone-input-container">
            <span class="country-code">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M13.6967 12.5708L16.98 15.9125C17.1271 16.0715 17.2065 16.2815 17.2015 16.498C17.1964 16.7145 17.1072 16.9206 16.9528 17.0725C16.7984 17.2244 16.5909 17.3102 16.3744 17.3117C16.1578 17.3133 15.9491 17.2305 15.7925 17.0808L12.5109 13.7425C11.2447 14.6964 9.66328 15.1334 8.08694 14.9652C6.51059 14.7969 5.05708 14.036 4.02072 12.8363C2.98436 11.6367 2.44259 10.0881 2.50511 8.50399C2.56763 6.91993 3.22978 5.41881 4.35747 4.3046C5.48516 3.19038 6.99412 2.54632 8.57883 2.50284C10.1635 2.45936 11.7055 3.0197 12.8926 4.07041C14.0797 5.12111 14.8232 6.58366 14.9725 8.16192C15.1218 9.74017 14.6657 11.3162 13.6967 12.5708ZM8.75004 13.3333C9.96562 13.3333 11.1314 12.8505 11.9909 11.9909C12.8505 11.1314 13.3334 9.96558 13.3334 8.75C13.3334 7.53443 12.8505 6.36864 11.9909 5.5091C11.1314 4.64956 9.96562 4.16667 8.75004 4.16667C7.53446 4.16667 6.36868 4.64956 5.50913 5.5091C4.64959 6.36864 4.16671 7.53443 4.16671 8.75C4.16671 9.96558 4.64959 11.1314 5.50913 11.9909C6.36868 12.8505 7.53446 13.3333 8.75004 13.3333Z" fill="#626F86"/>
                </svg>
            </span>
            <input 
                type="text" 
                class="phone-number" 
                id="phone"
                name="phone"
                maxlength="10" 
                placeholder="Search"
            >
        </div>
    </div>

</template>

<style scoped>

    .phone-container {
        display: flex;
        flex-direction: column;
        gap: 0.35rem;
    }

    .phone-input-container {
      display: flex;
      align-items: center;
      border: 2px solid #091E4224;
      border-radius: 8px;
      padding: 4px 12px;
      width: 100%;
      background-color: #fff;
      transition: all 0.3s ease;
        
    }

    .phone-input-container:focus-within {
        border-color: #388BFF; 
    }

    .country-code {
      font-weight: 400;
      
      color: #172B4D;
      font-size: 16px;
      /* line-height: 20px; */
      display: flex;
    }

    .phone-number {
      border: none;
      outline: none;
      flex: 1;
      font-size: 16px;
      padding: 5px 0 5px;
      background: transparent;
      color: #172B4D;
      /* line-height: 20px; */
    }
</style>