<script setup>
import { ref } from 'vue';

const password = ref('');
const showPassword = ref(false);

const togglePasswordVisibility = () => {
  showPassword.value = !showPassword.value;
};
</script>

<template>
    <div class="password-container">
        <label for="password" class="password-label">Password</label>
        <div class="password-input">
            <input
                :type="showPassword ? 'text' : 'password'"
                v-model="password"
                placeholder="Enter your password"
                class="password-field"
                id="password"
                name="password"
            />
            <span @click="togglePasswordVisibility" class="eye-icon">
                <svg
                v-if="showPassword"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="icon"
                >
                <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 12A3 3 0 1112 9a3 3 0 013 3zm7.2 0A10.95 10.95 0 0112 16.95 10.95 10.95 0 014.8 12 10.95 10.95 0 0112 7.05 10.95 10.95 0 0119.2 12z"
                />
                </svg>
                <svg
                v-else
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="icon"
                >
                <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13.875 18.825A10.95 10.95 0 0112 19.05a10.95 10.95 0 01-7.2-7.05A10.95 10.95 0 0112 4.95a10.95 10.95 0 016.675 2.825M9.88 9.88a3 3 0 104.24 4.24m0 0l4.12 4.12m-4.24-4.24L4.12 4.12"
                />
                </svg>
            </span>
        </div>
    </div>
    
  </template>
  
 
  
  <style scoped>

  .password-container {
    color: #626F86;
    display: flex;
    flex-direction: column;
    gap: 0.35rem;
  }

  .password-input:focus-within {
        border-color: #388BFF; 
        
    }

  .password-input {
    display: flex;
    align-items: center;
    border: 2px solid #091E4224;
    border-radius: 8px;
    padding: 8px 12px;
    width: 100%;
    background-color: #fff;
  }
  
  .password-field {
    flex: 1;
    border: none;
    outline: none;
    font-size: 16px;
    
  }
  
  .eye-icon {
    cursor: pointer;
    display: flex;
    align-items: center;
    padding: 0 5px;
  }
  
  .icon {
    width: 24px;
    height: 24px;
    color: #666;
  }
  </style>
  