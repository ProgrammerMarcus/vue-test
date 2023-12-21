<script setup lang="ts">
defineProps<{
  title: string
}>()
</script>

<template>
  <main>
    <div class="container">
      <h2>
        {{ title }}
      </h2>
      <slot>
        <!-- Book text in HTML -->
      </slot>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: var(--secondary);
  color: var(--text-d);
  font-family: var(--font);
  display: grid;
  place-items: center;
}
.container {
  background-color: var(--front);
  display: flex;
  flex-flow: column wrap;
  gap: 1.2rem;
  max-width: 720px;
  margin: min(20px, 2svw) 2svw 0 2svw;
  padding: min(60px, 5svw);
  min-height: 100lvh;
  border-radius: 3px;
  margin-bottom: 10px;
}
h2 {
  font-family: var(--font);
  font-size: 3rem;
}
</style>
