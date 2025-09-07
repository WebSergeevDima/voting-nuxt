<template>
    <NuxtLayout>
      <NuxtPage :transition="{
            name: 'page',
            mode: 'out-in'
        }" />
    </NuxtLayout>
</template>

<script setup lang="ts">
import "~/assets/styles/main.css"
</script>

<style scoped>
.page-enter-active,
.page-leave-active {
  transition: all 1s;
  opacity: 1;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
}
</style>