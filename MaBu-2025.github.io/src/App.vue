<script setup lang="ts">
import SidePicture from './components/SidePicture.vue'
import BasicInfoPanel from './components/BasicInfoPanel.vue'
import Registration from './components/Registration.vue'
import MyHeader from './components/MyHeader.vue'
import QuestionSection from './components/QuestionSection.vue'
</script>

<template>
  <div >
    <MyHeader/>
    <section id="home"> <SidePicture/> </section>
    <section id="info"><BasicInfoPanel/></section>
    <section id="rsvp"><Registration/></section>
    <section id="faq"><QuestionSection/></section>
    
  </div>
</template>

<style scoped>
* {
  max-width: 100%;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
