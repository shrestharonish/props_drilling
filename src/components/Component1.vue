<script setup>
// Importing the nested component
import Component2 from "./Component2.vue";

// Defining props using defineProps
const props = defineProps(["msg"]);
</script>

<template>
  <div>
    <!-- Displaying the received message from the parent component -->
    <h2>Component 1: {{ msg }}</h2>

    <!-- Passing the message as a prop to the nested Component2 -->
    <Component2 :msg="msg" />
  </div>
</template>

<style scoped></style>
