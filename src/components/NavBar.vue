<script setup>
import BankIcon from "./icons/BankIcon.vue"
</script>
<template>
    <nav>

<div class="flex justify-between">
  
    <BankIcon />


  <div>
    <a href="/">Home</a>
    <a href="/career">Career</a>
    <a href="/about">About</a>
    <a href="/security">Security</a>
  </div>

  <div>
    <button class="mr-3">Sign up</button>
    <button class="btn-primary-small">Login</button>
  </div>
</div>

</nav>
</template>

<style>

nav {
  border-radius: 6.25rem;
border: 1px solid var(--Grey-15, #262626);
background-color: #1a1a1a; padding: 0.75rem;
margin-top: 2.5rem;
}

</style>