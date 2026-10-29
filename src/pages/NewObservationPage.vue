<script setup>
import { ref } from 'vue'
const greeting = ref('Novo opažanje!')
</script>

<template>
  <p class="greeting">{{ greeting }}</p>
  <div>
  <q-btn color="white" text-color="black" label="Povratak", to="/" />
</div>
</template>

<style>
.greeting {
  color: red;
  font-weight: bold;
}
</style>