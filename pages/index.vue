<template>
  <div class="container flex flex-col justify-center">
    <section class="p-2 mt-8 mb-2 flex">
      <div class="flex flex-col justify-center p-4">
        <h1 class="text-left mb-4">What Can I Do?</h1>
        <p class="text-left mb-4">
          During this time it may be difficult to know how you can help or what
          you should say.
        </p>
        <p class="text-left mb-4">
          To help, we've compiled a guide of ways to help under three different
          themes: <nuxt-link to="/give" class="p-link">Giving</nuxt-link>,
          <nuxt-link to="/read" class="p-link">Reading</nuxt-link>, and
          <nuxt-link to="/showup" class="p-link">Showing Up.</nuxt-link> Pick
          the one that resonates most for you.
        </p>
        <p class="text-left mb-4">
          <!-- This is an open-source guide - so if you have a resource you'd like to
        add, you can do one of two things:
      </p> -->
        </p>
      </div>
      <div class="p-4">
        <img
          src="/images/blm-illustration.svg"
          alt="black lives matter illustration"
        />
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
img {
  height: 400px;
}

.p-link {
  text-decoration: underline;
}
</style>
