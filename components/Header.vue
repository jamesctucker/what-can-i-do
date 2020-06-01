<template>
  <header class="flex flex-row justify-between items-center p-4">
    <div>
      <nuxt-link to="/" class="nav-link m-2 text-xl font-bold">WCID</nuxt-link>
    </div>
    <div><Nav /></div>
  </header>
</template>

<script>
import Nav from "./Nav";
export default {
  name: "Header",
  components: {
    Nav
  }
};
</script>

<style scoped>
.nav-link {
  color: #202040;
}

.nav-link:hover {
  color: rgb(255, 20, 147);
}
</style>
