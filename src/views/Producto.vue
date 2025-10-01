<template>
  <h1>productos</h1>
  {{ productos }}
</template>

<script setup>
import { onMounted, ref } from "vue";

const productos = ref([]);

onMounted(() => {
  alert("hola mundo...");
  productos.value.push("hola",{},2);
});
</script>
