<script setup lang="ts">
</script>

<template>
    <header>
        <slot></slot>
        <h1>
            Library Test
        </h1>
    </header>
</template>

<style scoped>
    header {
        display: grid;
        grid-auto-flow: column;
        gap: 1rem;
        place-content: center start;
        width: 100%;
        height: 4rem;
        background-color: var(--shade);
        color: var(--text-l);
        font-family: var(--font);
        font-size: 2rem;
        padding: 1rem;
    }
</style>