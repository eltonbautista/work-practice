<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <div class="hero">
    <h1 class="hero__heading uk-heading-2xlarge">Hello World</h1>
  </div>
</template>

<style>
.hero {
  display: grid;
  justify-content: center;

  padding: 100px 0px;
}

.hero__heading {
  max-width: var(--max-w-xl);
  text-align: center;
}
</style>
