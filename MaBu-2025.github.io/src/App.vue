<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import SidePicture from './components/SidePicture.vue'
import MyHeader from './components/Header.vue'
</script>

<template>
  <div >
    <MyHeader/>
    <SidePicture/>
    
  </div>
</template>

<style scoped>
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
