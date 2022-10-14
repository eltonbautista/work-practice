<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import TheNavbar from "./components/molecules/TheNavbar.vue";
</script>

<template>
  <div id="app">
    <header>
      <!-- <nav>

        </nav> -->
      <TheNavbar msg="hello" />
    </header>

    <router-view />
  </div>
</template>

<style scoped></style>
