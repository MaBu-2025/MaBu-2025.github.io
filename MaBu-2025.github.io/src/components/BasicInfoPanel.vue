<script setup lang="ts">

</script>

<template>
  <div class="infoPanel">
    <div class="dearGuests">
      Milí hostia,
    </div>
    <div class="invite"> 

      ako už iste viete, 16.8.2025 je pre nás veľmi výnimočný dátum. V tento deň budeme oslavovať našu lásku a budeme radi, ak budete súčasťou tohto dňa aj Vy. 

  
    </div>
    <div class="place row">
      <div class="col-md-5 col-12">
        <div class="placeHeader">
          MIESTO A ČAS SOBÁŠA
        </div>
        <div class="invite">
          Sobáš sa uskutoční v kostole Ducha Svätého v Sielnici o 15:00 hod.

        </div>
        Kostol Ducha Svätého,<br>
        <a class="mapLink" href="https://maps.app.goo.gl/chhG8regMufJj9LS8" target="_blank">Sielnica 232, <br>
        962 31 Sielnica</a>
      
      </div>


    <div class="col-md-2 col-12 trasa">
      <a class="mapLink" href="https://maps.app.goo.gl/RCEnn4U3k5sBHxJc6" target="_blank">
      <i class="bi bi-car-front"></i><br/>
      trasa</a>
    </div>

    
    <div class="col-md-5 col-12">
      <div class="placeHeader">
          MIESTO SVADOBNEJ HOSTINY
        </div>
        <div class="invite">
          Svadobná hostina sa uskutoční v Penzióne Jáger na Tureckom Vŕšku.
        </div>
        PENZIÓN JÁGER na Tureckom Vŕšku,<br>
        <a class="mapLink" href="https://maps.app.goo.gl/Ea4KAygggYfGKh4z7" target="_blank">Piešť I 162, <br>
        962 12 Detva</a>
      </div>
    </div>
  </div>
  
</template>

<style scoped>
* {
  max-width: 100%;
}
@media (max-width: 767px) {
.trasa{
  padding-top: 50px;
  padding-bottom: 50px;
}

.placeHeader {
  padding-top: 20px;
  padding-bottom: 20px;
    font-weight: 100;
    font-family: "Cardo", italic; 
  font-size: larger;
  color: #738561;
}
  
.infoPanel{
  background-color: #f0f0f0;
  font-family: "Cardo", serif;  
  font-weight: 500;
  font-size: large;

  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.invite {
  padding-left:5%;
  padding-right:5%;
  padding-bottom: 20px;
  font-family: "Cardo", serif;  
  font-weight: 500;
  font-size: large;

}
}
@media (min-width: 768px) {
.trasa{
  margin: auto;
}

.placeHeader {
  padding-top: 20px;
  padding-bottom: 20px;
    font-weight: 100;
    font-family: "Cardo", italic; 
  font-size: x-large;
  color: #738561;
}
  
.infoPanel{
  background-color: #f0f0f0;
  font-family: "Cardo", serif;  
  font-weight: 500;
  font-size: larger;

  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.invite {
  padding-left:5%;
  padding-right:5%;
  padding-bottom: 20px;
  font-family: "Cardo", serif;  
  font-weight: 500;
  font-size: larger;

}
}

.mapLink{
  color:#a7a376;
  font-family: "Cardo", serif;
  font-weight: 500;
}
.mapLink:hover{
  color:white;
  background: #738561;
}
.place{
  background-color: #f0f0f0;
  padding-bottom: 50px;
  padding-top: 50px;
}
.dearGuests {
  padding-top: 20px;
  background-color: #f0f0f0;
    font-weight: 100;
    font-family: 'corinthia', italic; 
  font-size: 3.80rem;
  color: #738561;
}
</style>
