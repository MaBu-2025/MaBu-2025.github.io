<script setup lang="ts">



</script>

<template>

  <div class="container bckg">
    <div class="row" >
      <div class="col-0 col-sm-1">
      </div>
      <div class="col-12 col-sm-6 names">
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
      <div class="col-12 col-sm-4">
          <img class="myimg" src="../assets/foto_zasnuby.jpg" alt="Image"/>
      
      </div>
    
      <div class="col-0 col-md-1">

      </div>
  </div>
</div>
<!-- 
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
   <div><a class="registration" target="_blank" href="https://www.google.com">Prosíme, potvrďte Vašu účasť</a></div>
  
      <div class="placeholder"></div>
    </div>
  </div></div>-->
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

.bckg{
  background-color: #738561;

  padding: 20px;
  margin: 5.55rem 0 0 0;
  /*border-radius: 10px;*/
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  max-width: 4900px; /* Adjust the max-width as needed
  
  background-color: #454411;
  */
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
@media (max-width: 540px) {
  .firstname {
    color:white;
    font-family: "Cardo", serif;
    font-size:xx-large;
    letter-spacing: 2px;
    font-weight: 100;
    font-style:normal;
    margin: 0;
  }

  .surname {
    color:#d4d1b8;
    font-weight: 100;
    font-family: 'corinthia', italic;  
    font-size: 3.2em;
  }
    .names {
    margin-top: 50px;
    margin-bottom: 50px;
    }
}
@media (min-width: 540px) {
  .firstname {
    color:white;
    font-family: "Cardo", serif;
    font-size:large;
    letter-spacing: 2px;
    font-weight: 100;
    font-style:normal;
    margin: 0;
  }

  .surname {
    color:#a7a376;
    font-weight: 100;
    font-family: 'corinthia', italic;  
    font-size: xx-large;
  }
  
  .names {
  margin-top: auto;
  margin-bottom: auto;
  }
}
@media (min-width: 992px) {
  .firstname {
    color:white;
    font-family: "Cardo", serif;
    font-size:xx-large;
    letter-spacing: 2px;
    font-weight: 100;
    font-style:normal;
    margin: 0;
  }

  .surname {
    color:#d4d1b8;
    font-weight: 100;
    font-family: 'corinthia', italic;  
    font-size: 3.2em;
  }
  
  .names {
  margin-top: auto;
  margin-bottom: auto;
  }
}
@media (max-width: 1400px)
{
  .myimg{
    width: 100%; 
    height: auto;
    border-radius: 1%;
    margin-top: auto;
    margin-bottom: auto;
  }
}
@media (min-width: 1400px) {
  .myimg{
    width: 80%; 
    height: auto;
    border-radius: 1%;
    margin-top: auto;
    margin-bottom: auto;
}
}

.date {
  color:#454411;
  font-weight: 800;
  font-family: 'corinthia', italic;  
  font-size: 2.8em;
}

</style>
