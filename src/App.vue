<script setup lang="ts">
import BookReader from './components/BookReader.vue'
import MainHeader from './components/MainHeader.vue'
import BookLogo from './components/icons/BookLogo.vue'
import BookSelection from './components/BookSelection.vue'
import './assets/reset.css'
import './assets/variables.css'
</script>

<template>
  <MainHeader>
    <BookLogo />
  </MainHeader>
  <BookReader title="Test">
    <p>
      A tale begun in other days, When summer suns were glowing— A simple chime, that served to time
      The rhythm of oar rowing— Whose echoes live in memory yet, Though envious years would say
      ‘forget.’
    </p>
    <p>
      Come, hearken then, ere voice of dread. With bitter tidings laden, Shall summon to unwelcome
      bed A melancholy maiden! We are but older children, dear, Who fret to find our bedtime near.
    </p>
    <p>
      Without, the frost, the blinding snow. The storm-wind’s moody madness— Within, the firelight’s
      ruddy glow, And childhood’s nest of gladness. The magic words shall hold thee fast: Thou shalt
      not heed the raving blast.
    </p>
  </BookReader>
  <BookSelection />
</template>

<style scoped></style>
