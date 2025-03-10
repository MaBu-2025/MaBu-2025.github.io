<script setup lang="ts">


</script>

<template>
  <div>
    <div class="names">
      <div class="firstname">BARBORA</div>
      <div class="surname">Jurašková</div>
      <div class="surname">a</div>
      <div class="firstname">MARTIN</div>
      <div class="surname">Izrael</div>
    </div>  

    <div class="std">Save the date</div>
    <div class="date">16.8.2025</div>

    
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
.winter {
  color:bisque;
}
.std {
  color:#a7a376;
  font-weight: 100;
  font-family: "Cardo", serif;
  font-size: 1.6em;
}
.firstname {
  color:#a7a376;
  font-family: "Cardo", serif;
  font-size: medium;
  letter-spacing: 2px;
  font-weight: 100;
  font-style: normal;
  margin: 0;
}
.surname {
  color:#454411;
  font-weight: 100;
  font-family: 'corinthia';  
  font-size: 3.2em;
}
.date {
  color:#454411;
  font-weight: 800;
  font-family: 'corinthia';  
  font-size: 3.2em;
}
.names {
  margin-top: 100px;
  margin-bottom: 200px;
}
</style>
