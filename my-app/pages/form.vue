<template>
    <h1>Hello, World!</h1>
</template>

<script setup>
if (process.server) {
    console.log('Hello, World!');
}
</script>
