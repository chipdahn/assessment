<script setup>
import router from "@/router";
import { onMounted } from "vue";


function goToLogin () {
    router.push('/login')
}

onMounted(() => {
    goToLogin()
})

</script>

<template>
    
</template>

<style scoped>

</style>
