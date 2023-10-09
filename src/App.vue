<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
      <RouterLink to="/login">Login</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

nav {
  text-align: center;
  border-bottom: 1px solid #000;
  padding: 20px 0;
}
nav a {
  text-decoration: none;
  color: #555;
  font-size: 1.3em;
  padding: 0px 10px;
}

nav a:hover,
nav a:focus {
  color: #000;
}
</style>
