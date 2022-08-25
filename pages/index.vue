<template>
  <div>
    <NuxtLayout>
        <TheHero />
        <div class="container">
          <TheContent />
        </div>
    </NuxtLayout>
  </div>
</template>

<script setup>
import TheHero from '~~/components/TheHero.vue';
import TheContent from '~~/components/TheContent.vue';

</script>

<style>

</style>