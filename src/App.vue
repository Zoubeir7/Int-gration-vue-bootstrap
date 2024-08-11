<template>
<div id="app"> 
  <MonNavbar msg="Welcome to Your Vue.js App"/>
  <JumButton/>
  <CTA/>
  <AppCards/>

</div>
</template>

<script>
import JumButton from './components/JumButton.vue';
import CTA from './components/CTA.vue';
import MonNavbar from './components/MonNavbar.vue';
import AppCards from './components/AppCards.vue';


export default {
  name: 'App',
  components: {
    MonNavbar,
    JumButton,
    CTA,
   AppCards
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
</style>
