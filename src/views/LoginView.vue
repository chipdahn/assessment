<script setup>
import BrandLogo from '@/components/icons/BrandLogo.vue';
import PasswordInput from '@/components/LoginForm/PasswordInput.vue';
import PhoneNumber from '@/components/LoginForm/PhoneNumber.vue';

</script>

<template>
    <div class="login-form">
        <div class="heading">
            <div>
                <svg height="512" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><title/><polyline points="244 400 100 256 244 112" style="fill:none;stroke:#000;stroke-linecap:round;stroke-linejoin:round;stroke-width:48px"/><line style="fill:none;stroke:#000;stroke-linecap:round;stroke-linejoin:round;stroke-width:48px" x1="120" x2="412" y1="256" y2="256"/></svg>
            </div>
            <div class="logo-container">
                <BrandLogo/>
            </div>
        </div>
        <div class="login-container">
                <div class="login-form-container">
                    <div class="login-form-heading">
                        <p>PROCUREMENT</p>
                        <h2>Sign in to your account</h2>
                    </div>
                    <form action="">
                        <PhoneNumber/>
                        <PasswordInput/>
                        <div class="keep-container">
                            <input type="checkbox" name="keep" id="keep">
                            <label for="keep">Keep me signed in</label>
                        </div>
                        <button type="submit">Proceed</button>
                    </form>
                    <div class="forget-divider">
                        <hr>
                        <div class="forgot-passowrd-container">
                            <button type="button">
                                Forgot Password?
                            </button>
                        </div>
                    </div>
                </div>
        </div>
    </div>
</template>

<style scoped>

.heading {
    height: 5%;
    display: flex ;
}

.heading div {
    height: 100%;
}

.logo-container {
    flex: 1;
    display: flex;
    justify-content: center;
}

.login-container {
    flex: 1;
}

.heading div svg {
    height: 2rem;
}

.login-form {
    width: 100%;
    padding: 0.5rem;
    background-color: #091E4224;
    height: 100vh;
    margin: 0 auto;
}

.login-container {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 95%;
}

.login-form-container {
    padding: 2rem;
    border-radius: 16px;
    background-color: white;
    box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
    width: 380px;
}

.login-form-heading {
    margin-bottom: 1rem;
}

.login-form-heading p {
    color: #626F86;
    font-size: 12px;
    line-height: 16px;
    text-transform: uppercase;
    margin-bottom: 0.5rem;
}

.login-form-heading h2 {
    color: #172B4D;
    font-weight: 600;
}

.keep-container {
    display: flex;
    padding-left: 0.5rem;
    align-items: center;
    gap: 0.8rem;
    margin: 7px 0;
    
}

.keep-container label {
    color: #44546F;
    font-size: 14px;
}

input[type='checkbox'] {
    border: 2px solid #091E4224;
    /* outline: 2px solid #091E4224;
    border: 8px; */
}

form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

button[type='submit'] {
    width: 100%;
    padding: 15px;
    background-color: #0C66E4;
    color: white;
    font-weight: 600;
    border: none;
    outline: none;
    border-radius: 8px;
    cursor: pointer;
}

.forget-divider {
    margin-top: 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.forget-divider hr {
    border-color: #091E4224;
    border-width: 0.1rem;
}

.forget-divider div {
    display: flex;
    justify-content: center;
}

button[type='button'] {
    background-color: transparent;
    border: none;
    color: #44546F;
    cursor: pointer;
}

</style>