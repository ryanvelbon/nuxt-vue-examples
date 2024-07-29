<script setup>
const x = ref(Math.random())
const y = useState('some-key', () => Math.random())
</script>

<template>
    <h1>ref vs. useState</h1>
    <div>{{ x }}</div>
    <div>{{ y }}</div>
</template>
