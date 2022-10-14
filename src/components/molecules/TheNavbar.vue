<template>
  <nav class="uk-navbar-container" uk-navbar>
    <div class="uk-navbar-left">
      <ul class="uk-navbar-nav">
        <li class="uk-active">
          <a href="#">{{ logo }}</a>
        </li>
        <li>
          <a href="#">{{ title }}</a>
        </li>
        <li>
          <a href="#">{{ navLabel }}</a>
          <div class="uk-navbar-dropdown">
            <ul class="uk-nav uk-navbar-dropdown-nav">
              <li class="uk-active"><a href="#">Active</a></li>
              <li><a href="#">Item</a></li>
              <li><a href="#">Item</a></li>
            </ul>
          </div>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script setup lang="ts">
defineProps<{
  logo: string;
  title: string;
  navLabel: string;
}>();
</script>

<style>
.uk-navbar-container {
  display: block;
  padding: 0 var(--p-sm);
}

.uk-navbar-left {
  display: grid;
  justify-items: center;
}

.uk-navbar-nav {
  display: grid;
  grid-auto-flow: column;
  max-width: var(--max-width-xl);
  width: 100%;
}

.uk-navbar-nav > li:nth-child(1) {
  justify-self: start;
  padding-left: var(--p-lg);
}

.uk-navbar-nav > li:nth-child(3) {
  justify-self: end;
  padding-right: var(--p-lg);
}
</style>
