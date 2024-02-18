<!-- Component2.vue -->

<script setup>
// Defining props using defineProps
const props = defineProps(["msg"]);
</script>

<template>
  <div>
    <!-- Displaying a title for Component2 -->
    <h2>The Last Component</h2>

    <!-- Displaying the received message from the parent component -->
    <p>Received data prop in Component2: {{ msg }}</p>
  </div>
</template>

<style scoped></style>
