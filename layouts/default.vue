<template>
  <div>
    <TheNav />
    Default Layout
    <slot />
    <TheFooter />
  </div>
</template>

<script setup>
import TheNav from '~~/components/TheNav.vue';
import TheFooter from '~~/components/TheFooter.vue';

</script>

<style>

</style>