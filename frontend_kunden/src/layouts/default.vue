<script setup lang="ts">

</script>
<template>
  <div class="flex flex-col min-h-screen">
    <Fheader />

    <main class="flex-auto">
      <slot />
    </main>

    <Ffooter />
  </div>
</template>
