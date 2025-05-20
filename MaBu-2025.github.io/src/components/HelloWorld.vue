<script setup lang="ts">

import MyHeader from './MyHeader.vue'

</script>

<template>
  <div class="backimg">
    <MyHeader/>
    <div class="overlay"></div>
    <div class="head_info">
      <div class="names">
        <div class="babu">
          <div class="firstname">BARBORA</div>
          <div class="surname">Jurašková</div>
        </div>
        <div class="surname">a</div>
        <div class="mardo">
          <div class="firstname">MARTIN</div>
          <div class="surname">Izrael</div>
        </div>
      </div>  

      <div class="std">Tešíme sa na Vás</div>
      <div class="date">16. augusta 2025</div>
      <div class="std">v kostole Ducha Svätého v Sielnici</div>
    <!-- <div><a class="registration" target="_blank" href="https://www.google.com">Prosíme, potvrďte Vašu účasť</a></div>
  -->
      <div class="placeholder"></div>
    </div>
  </div>
  <!--<div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Learn more about IDE Support for Vue in the
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      >Vue Docs Scaling up Guide</a
    >.
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>-->
</template>

<style scoped>
.backimg{
  position: relative;
  width: 100%;
  height: 800px; /* Adjust the height as needed */
  overflow: hidden;
}
.placeholder{
  min-height: 100vh;
}
.registration{
  color:#a7a376;
  font-family: "Cardo", serif;
  font-weight: 800;
  font-size: larger;
  margin-top:100px;
  padding: 20px 10px;
}
.registration:hover{
  color:white;
  background: #454411;
  font-weight: 200;
}
.overlay {
  background-size: cover;
  width: 100%;
  background-image: url('mabu_foto_sirka.jpg');
  background-position: center;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 0.99; 
}
.head_info{
  position: relative;
  margin: 0 auto;
  min-width: 500px;
  padding-top: 30px;
}
.babu{
  margin-right: 120px;
}
.mardo{
  margin-left: 120px;
}
.std {
  color:#a7a376;
  font-weight: 100;
  font-family: "Cardo", serif;
  font-size: 1.2em;
}
.firstname {
  color:#a7a376;
  font-family: "Cardo", serif;
  font-size:xx-large;
  letter-spacing: 2px;
  font-weight: 100;
  font-style:normal;
  margin: 0;
}

.surname {
  color:#454411;
  font-weight: 100;
  font-family: 'corinthia', italic;  
  font-size: 3.2em;
}
.date {
  color:#454411;
  font-weight: 800;
  font-family: 'corinthia', italic;  
  font-size: 2.8em;
}
.names {
  margin-top: 50px;
  margin-bottom: 150px;
}
</style>
