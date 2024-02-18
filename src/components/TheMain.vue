<script setup>
import { ref } from "vue";

// child component to which the prop is to be passed
import Component1 from "./Component1.vue";

const greeting = ref("Hello from parent");
</script>
<template>
  <div>
    <h1>The Main Component</h1>

    <!-- Passing greeting as a prop -->
    <Component1 :msg="greeting" />
  </div>
</template>

<style scoped></style>
