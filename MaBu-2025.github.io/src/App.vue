<script setup lang="ts">
import SidePicture from './components/SidePicture.vue'
import BasicInfoPanel from './components/BasicInfoPanel.vue'
import Registration from './components/Registration.vue'
import MyHeader from './components/Header.vue'
</script>

<template>
  <div >
    <MyHeader/>
    <SidePicture/>
    <BasicInfoPanel/>
    <Registration/>
    
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
