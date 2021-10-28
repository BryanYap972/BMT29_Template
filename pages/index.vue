<template>
  <div class="contain flex flex-col justify-center items-center">
    <h1 class="text-9xl mb-20">Hands-on time!</h1>
    <NuxtLink class="text-3xl text-blue-400" to="/tailwindDemo"
      >Click here for Tailwind demo</NuxtLink
    >
    <br />
    <NuxtLink class="text-3xl text-purple-400" to="/NuxtDemo"
      >Click here for NuxtJS concepts demo</NuxtLink
    >
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.contain {
  height: 100vh;
}
</style>
