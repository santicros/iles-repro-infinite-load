<template>
  <button @click="inc">{{ count }}</button>
</template>
<script setup lang="ts">
import { ref } from "vue";

const count = ref(0);
const inc = () => count.value++;
</script>
