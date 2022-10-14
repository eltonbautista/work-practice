<script setup lang="ts">
import TheNavbar from "./components/molecules/TheNavbar.vue";
</script>

<template>
  <div id="app">
    <header>
      <!-- <nav>

        </nav> -->
      <TheNavbar logo="Logos" nav-label="Navigation" title="Our World" />
    </header>

    <router-view />
  </div>
</template>

<style scoped>
#app {
  background: var(--white);
}
</style>
