<script setup>
import { ref } from 'vue';
import axios from 'axios';

const username = ref('john')
const email = ref('')
const password = ref('')

const signup = async () => {
    console.log(`${username.value} ${email.value} ${password.value}`);
    // save the value
    axios.post('');
}
</script>

<template>
    <form @submit.prevent="signup">
        <input type="text" placeholder="Enter username" v-model="username">
        <input type="email" placeholder="Enter email" v-model="email">
        <input type="password" placeholder="Enter password" v-model="password">
        <input type="submit">
    </form>
</template>

<style scoped>
input{
    display: block;
    margin-bottom: 10px;
}
</style>