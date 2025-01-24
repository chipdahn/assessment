<script setup>
</script>

<template>
    <div class="phone-container">
        <label for="phone-label">Phone</label>
        <div class="phone-input-container">
            <div class="flag"></div>
            <span class="country-code">+234</span>
            <input 
                type="tel" 
                class="phone-number" 
                id="phone"
                name="phone"
                maxlength="10" 
                pattern="[0-9]{10}"
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
      padding: 8px 12px;
      width: 100%;
      background-color: #fff;
      transition: all 0.3s ease;
        
    }

    .phone-input-container:focus-within {
        border-color: #388BFF; 
    }

    .flag {
      width: 30px;
      height: 20px;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/7/79/Flag_of_Nigeria.svg'); /* Link to the Nigerian flag */
      background-size: contain;
      background-position: center;
      margin-right: 10px;
      
    }

    .country-code {
      font-weight: 400;
      
      color: #172B4D;
      font-size: 16px;
      /* line-height: 20px; */
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