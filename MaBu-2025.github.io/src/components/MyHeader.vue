<script setup lang="ts">
  import { ref } from 'vue'
  const menuOpen = ref(false)
  const toggleMenu = () => {
    menuOpen.value = !menuOpen.value
  }
  
const scrollToSection = (id: string) => {
  const el = document.getElementById(id)
  if (el) {
    el.scrollIntoView({ behavior: 'smooth', block: 'center' })
    menuOpen.value = false 
  }
}
</script>

<template>
   <header class="header">
    <button class="burger-button" @click="toggleMenu">
      ☰
    </button>
    <div class="nav-container" :class="{ open: menuOpen }">
      <button class="nav-button" @click="scrollToSection('home')">DOMOV</button>
      <button class="nav-button" @click="scrollToSection('info')">INFORMÁCIE</button>
      <button class="nav-button" @click="scrollToSection('rsvp')">RSVP</button>
      <button class="nav-button" @click="scrollToSection('faq')">FAQ</button>
    </div>
  </header>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.header {
  padding: 1rem 2rem;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: white;
  z-index: 1000;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  opacity: 0.9;
}

/* --- Burger Button --- */
.burger-button {
  margin: 0 auto;
  display: none;
  background: none;
  border: none;
  font-size: 2rem;
  cursor: pointer;
  color: #454411;

}

/* --- Nav container --- */
.nav-container {
  display: flex;
  justify-content: flex-end;
  flex-wrap: wrap;
  margin-right: 5%;
}
@media (max-width: 767px) {
  .nav-button {
    font-family: "Cardo", serif;
    color: #454411;
    background-color: white;
    padding: 0.7rem 0.7rem;
    margin: 0.3rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: medium;
    letter-spacing: 2px;
    font-weight: 100;
    font-style: normal;
  } 
}

@media (min-width: 767px) {
  .nav-button {
    font-family: "Cardo", serif;
    color: #454411;
    background-color: white;
    padding: 0.7rem 1.2rem;
    margin: 0.3rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: large;
    letter-spacing: 2px;
    font-weight: 100;
    font-style: normal;
  }
}

.nav-button:hover {
  background-color: #454411;
  color: white;
}

/* --- Responsive Styling --- */
@media (max-width: 540px) {
  .burger-button {
    display: block;
  }

  .nav-container {
    display: none;
    flex-direction: column;
    align-items: stretch;
    margin-top: 1rem;
  }

  .nav-container.open {
    display: flex;
  }

  .nav-button {
    width: 100%;
  }
}
</style>
