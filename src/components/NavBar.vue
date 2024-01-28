<script setup>
import BankIcon from "./icons/BankIcon.vue";
</script>

<script>
export default {
  computed: {
    currentRoute() {
      return this.$route.name;
    },
  },
};

</script>
<template>
  <nav>
    <div class="flex justify-between items-center">
      <BankIcon />

      <div>
        <a class="nav-link" :class="{ active: currentRoute =='home' }" href="/">Home</a>
        <a class="nav-link" :class="{ active: currentRoute =='career' }" href="/career">Career</a>
        <a class="nav-link" :class="{ active: currentRoute =='about' }" href="/about">About</a>
        <a class="nav-link" :class="{ active: currentRoute =='security' }" href="/security">Security</a>
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
  background-color: #1a1a1a;
  padding: 0.75rem;
  margin-top: 2.5rem;
}

.nav-link {
  margin-right: 1.62rem;
  margin-top: 20px;
}

.nav-link.active {
  border-radius: 82px;
  background-color: #262626;
  padding: 0.62rem 1.12rem;
}
</style>
