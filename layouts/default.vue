<script lang="ts" setup>
console.log("Loaded");
</script>

<template>
  <section class="grid height">
    <LayoutSidebar />
    <div>
      <slot />
    </div>
  </section>
</template>

<style scoped>
.grid {
  display: grid;
  grid-template-columns: 1fr 6fr;
}
.height {
  min-height: 100vh;
}
</style>
