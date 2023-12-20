<script setup lang="ts">
import BookReader from './components/BookReader.vue';
import MainHeader from './components/MainHeader.vue'
import BookLogo from './components/icons/BookLogo.vue'
import './assets/reset.css'
import './assets/variables.css'
</script>

<template>

  <MainHeader>
    <BookLogo />
  </MainHeader>
  <BookReader title="Test" text="Test" />

</template>

<style scoped>
</style>
