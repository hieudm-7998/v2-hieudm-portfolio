<template>
  <div class="app container">
    <Header />
    <Nuxt />
  </div>
</template>

<script>
export default {};
</script>

<style>
.app {
  font-family: "Inter", sans-serif;
}

.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}
.primary-color{
  color: #ff971a;
}
</style>