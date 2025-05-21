<script setup lang="ts">
import Question from './Question.vue'

</script>

<template>
  <div class="questionSection">
    <h2 class="questionSectionHeader">ČO BY VÁS MOHLO ZAUJÍMAŤ </h2>

    <Question 
      question="Čo najviac poteší mladomanželov?" 
      answer="Barbora a Martin nie sú nároční ľudia. Radi si sami zariadia a kúpia veci, ktoré potrebujú alebo sa im páčia. Preto si nerobte starosti s výberom najlepších nerezových hrncov alebo iných darov. Bude pre Vás, ale aj pre nich jednoduchšie dať Váš dar do peknej obáločky."
    />
   
    <Question 
      question="Ako je riešené ubytovanie na svadbe?" 
      answer="Penzión Jáger nemá až tak veľkú kapacitu ubytovania, aby sme sa tam zmestili úplne všetci. To však neznamená, že všetci budete musieť ísť domov, alebo spať niekde mimo Detvy. Práve naopak, v penzióne Jáger je ešte niekoľko voľných lôžok a zároveň Detva ponúka aj iné možnosti ubytovania. Preto, ak máte záujem spať na mieste svadobnej hostiny alebo v okolí, neváhajte to napísať do formulára. Naši mladomanželia Vám radi pomôžu niečo nájsť."
    />

    <Question 
      question="Prečo nie sú na svadbu pozvaní všetci, ktorých poznáme a máme radi?" 
      answer="Barbora a Martin by najradšej oslavovali so všetkými, na ktorých im záleží. No aby si tento deň mohli naplno užiť a venovať sa každému aspoň chvíľu, rozhodli sa pre užší okruh hostí. Veria, že ich rozhodnutie prijmete s pochopením."
    />
    
    <Question 
      question="Priniesť kvety alebo nie?" 
      answer="Ak by ste chceli priniesť kvety, je to od Vás veľmi milé, no úprimne, nikto sa nenahnevá, ak túto tradíciu tentoraz vynecháte. Kvety sú krásne, ale sú aj krehké, rýchlo vädnú a bolo by náročné im dať tú správnu opateru, akú by si zaslúžili. Ďakujeme, že to chápete, budeme radšej, ak si spolu vychutnáme pekné chvíle a nebudeme musieť riešiť vázy."
    />
    
    <Question 
      question="Ako sa obliecť?" 
      answer="Dámy, najdôležitejšie je, aby ste sa cítili pohodlne a samy sebou. Či už si zvolíte šaty kvetované, krátke, dlhé, alebo aj čierne, naozaj sa nemusíte báť, že by to bolo nevhodné. Jediná prosba, bielu nechajte neveste. Páni predpokladáme, že vy sa stresovať nebudete vôbec, vy len zoberte oblek a tiež buďte sami sebou."
      />
    
    <Question 
      question="Odvezie ma niekto domov zo svadby, ak si chcem užiť večer aj s trochou alkoholu?" 
      answer="Odvoz z hostiny bude zabezpečený, počítame s tým, že si budete chcieť večer naplno užiť, a preto bude k dispozícii šofér, ktorý vás bezpečne odvezie domov. Odvoz z obradu na hostinu však zabezpečený nebude, preto prosíme, aby ste si túto časť dopravy vyriešili individuálne (napr. medzi sebou alebo vlastným autom)."
    />
    <!--
    <Question 
      question="" 
      answer=""
    />-->
    
  </div>
  
</template>

<style scoped>
.questionSection {

  text-align: center;
  background-color: #f0f0f0;


  box-shadow: 0 4px 8px rgba(#738561, 0.1);
}
.questionSectionHeader {
  padding-top: 100px;

  margin-bottom: 50px;
  font-size: 3.2rem;
  font-weight: 100;
  font-family: "Cardo", italic; 
  font-size: x-large;
  color:#a7a376;
}
</style>
