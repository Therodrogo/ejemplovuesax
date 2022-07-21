<template>
  <div>

    <!-- <BarraNavegacion/> -->
    <BarraMenu/>

    <Nuxt/>


  </div>
  
</template>

<script>

import Vue from 'vue'
import Vuesax from 'vuesax'

import 'vuesax/dist/vuesax.css'
import BarraNavegacion from '../components/BarraNavegacion.vue'
import BarraMenu from '../components/BarraMenu.vue' //Vuesax styles
Vue.use(Vuesax, {
  colors: {
      primary:'#DE6283',
      success:'rgb(23, 201, 100)',
      danger:'rgb(242, 19, 93)',
      warning:'rgb(255, 130, 0)',
      dark:'rgb(36, 33, 69)'
    }
})


export default {
    components: { BarraNavegacion, BarraMenu }
}
</script>

<style>

.contenedor{
  margin-top: 50px;
  margin-left: 10%;
  margin-right: 10%;

  font-family: 'Roboto', sans-serif;
}

</style>