<template>
  <div>
    <nuxt-link to="/give" class="nav-link m-2">Give</nuxt-link>
    <nuxt-link to="/read" class="nav-link m-2">Read</nuxt-link>
    <nuxt-link to="/showup" class="nav-link m-2">Show Up</nuxt-link>
  </div>
</template>

<script>
export default {
  name: "Nav"
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
