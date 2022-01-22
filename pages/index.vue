<template>
    <div>
        <h1>{{ title }}</h1>
        <Hello />
    </div>
</template>

<script setup lang="ts">
const title = ref<string>('Home Page')
</script>
