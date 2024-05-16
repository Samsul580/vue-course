<script setup>
const imgInfo = {
  src: 'https://images.unsplash.com/photo-1542831371-29b0f74f9713?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
  alt: 'Image Info',
  height: 400,
  width: 400
}
</script>

<template>
  <div>
    <img :="imgInfo" />
  </div>
</template>
