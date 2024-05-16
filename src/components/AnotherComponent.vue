<script setup>
const myMessage = 'Yellow World'
const herMessage = 'White World'
const num = 100
function add(a, b) {
  return a + b
}
</script>

<template>
  <h1>Nested Component</h1>
  <h2>My Message: {{ myMessage }}</h2>
  <h2>Her Message: {{ herMessage }}</h2>
  <h3>Number: {{ num }}</h3>
  <h3>Number + 50: {{ num + 50 }}</h3>
  <h3>Add function call: {{ add(200, 300) }}</h3>
</template>
