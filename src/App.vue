<script setup>


</script>

<template>
  <div class="nav">
 <router-link to="/" class="nav-item">Home</router-link>
  <router-link to="/about" class="nav-item">About</router-link>
  <router-link to="/service" class="nav-item">Services</router-link>
  <router-link to="/signup" class="nav-item">Signup</router-link>
  </div>
  <router-view></router-view>

</template>

<style scoped>
button {
  border-radius: 10px;
  background-color:lightgreen;
  padding: 10px;
}
input{
    display: block;
    margin-bottom: 10px;
    background-color: lightgreen;
}
.nav {
  padding-top: 0;
}
.nav-item {
  background-color: rgb(144, 180, 238);
  color: white;
  text-decoration: none;
  padding: 0 28px;
  font-weight: bold;
}

</style>