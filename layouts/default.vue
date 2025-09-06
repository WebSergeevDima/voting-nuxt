<template>
  <div class="wrapper">
    <aside class="left">
      <ul>
        <li>
          <NuxtLink to="#">
            <Icon name="icons:home" size="24" />
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">
            <Icon name="icons:door" size="24" />
          </NuxtLink>
        </li>
      </ul>
    </aside>
    <main>
      <slot />
    </main>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.wrapper {
  display: flex;
  gap: 20px;
}

  .left {
    border-right: 1px solid var(--color-gray);
    padding: 28px;
    height: 100vh;
  }

  ul {
    margin: 0;
    padding: 0;
    list-style: none;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
  }

</style>

