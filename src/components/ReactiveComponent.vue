<script setup>
import { reactive } from 'vue'
let intialState = reactive({
  count: 0
})
</script>

<template>
  <h1>Count: {{ intialState.count }}</h1>
  <button @click="intialState.count++">Increament</button>
</template>
