<script setup>
const myGithub = 'https://github.com/Samsul580'
const image =
  'https://images.unsplash.com/photo-1542831371-29b0f74f9713?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
const altText = 'Test Alt'
</script>

<template>
  <p><a :href="myGithub">My Github</a></p>
  <img :src="image" :alt="altText" style="width: 50%; height: 10%" />
</template>
