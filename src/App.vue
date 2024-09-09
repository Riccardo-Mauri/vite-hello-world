<script>
//1- Importazione del componenente necessario che voglio aggiungere qua
import AppTitle from './components/AppTitle.vue';

export default {
  data() {
    return { 
    }
  },
  //2- Dichiarazione del componente 
  components: {
    AppTitle
  },
  
}
</script>

<template>
  <div>
    <!--3- Utilizzo del componenete -->
    <AppTitle />
  </div>
</template>

<style scoped>

</style>
