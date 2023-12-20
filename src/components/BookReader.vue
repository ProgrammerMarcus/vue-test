<script setup lang="ts">
defineProps<{
  title: string, text: string
}>()
</script>

<template>
    <main>
        <h2>
            {{ title }}
        </h2>
        <p>
            {{ text }}
        </p>
    </main>
</template>

<style scoped>
    main {
        width: 512px;
        height: 512px;
        background-color: aqua;
    }
</style>