<template>
  <div>
    <header>
      <nav>
        <p>Products Merch</p>
      </nav>
    </header>
  </div>
  <div>
    <slot></slot>
  </div>
  <footer>
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/about">About</NuxtLink></li>
      <li><NuxtLink to="/products">Products</NuxtLink></li>
    </ul>
  </footer>
</template>

<script setup>
definePageMeta({
  layout: "products",
});
</script>

<style>
.router-link-exact-active {
  color: green;
}
</style>
