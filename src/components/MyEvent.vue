<script setup>
import { ref } from 'vue'
let count = ref(0)
const increament = () => count.value++
const decreament = () => count.value--

const submitHandler = (e) => {
  e.preventDefault()
  alert('Valid Credentials')
}
</script>

<template>
  <h1>Count : {{ count }}</h1>
  <div>
    <button @:click="increament">Increment</button>
    <button @:click="decreament">Decrement</button>
  </div>

  <form @:submit="submitHandler">
    <input type="text" placeholder="Please Enter Your Name" />
    <input type="email" placeholder="Please Enter Your Email" />
    <button type="submit">Submit</button>
  </form>
</template>
