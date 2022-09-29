<template>
  <div class="content">
    <HeaderView/>
    <NavbarView/>
    <ContentView/>
    <FooterView/>

  </div>
</template>

<script>

import HeaderView from "./components/HeaderView.vue";
import NavbarView from "./components/NavbarView.vue";
import ContentView from "./components/ContentView.vue";
import FooterView from "./components/FooterView.vue";


export default {
  name: 'App',
  components: {
    
    HeaderView,
    
    ContentView,
    FooterView,
    NavbarView
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
  margin-top: 60px;
}
</style>
