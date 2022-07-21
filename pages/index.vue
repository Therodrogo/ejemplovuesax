<template>
  <div class="contenedor">

    <vs-row>
      <vs-col :key="index" v-for="col,index in 10" w="3">
          <Carta/>
      </vs-col>
    </vs-row>

    
  </div>

  
  
  
</template>

<script>
import Carta from '../components/Carta.vue';
import BarraMenu from '../components/BarraMenu.vue';
export default {
    name: "IndexPage",
    components: {
    Carta,
    BarraMenu
}
}
</script>

<style scoped>

</style>
