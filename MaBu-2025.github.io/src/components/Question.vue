
<script setup lang="ts">
  defineProps(['question', 'answer'])
</script>

<template>
  <div class="qaa">
    <h2 class="question">
      {{ question }}
    </h2>
    <div class="answer"> 
      {{ answer }}

    </div>
  </div>
  
</template>

<style scoped>
* {
  max-width: 100%;
}
.qaa{
  padding: 20px 10%;
  margin-bottom: 20px;
  box-shadow: 0 4px 8px rgba(73,85,61, 0.1);
}
.question{
  font-family: "Cardo", serif;
  font-weight: 500;
  font-size: x-large;
  color: #738561;
}
.answer{
  font-family: "Cardo", serif;
  font-weight: 100;
  font-size: large;
}

</style>
