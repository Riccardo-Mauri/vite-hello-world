<script>
//1- Importazione del componenente necessario che voglio aggiungere qua
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return { 
    }
  },
  //2- Dichiarazione del componente 
  components: {
    AppTitle,
    AppHero
  },
  
}
</script>

<template>
  <div>
    <!--3- Utilizzo del componenete -->
    <AppTitle />
    <AppHero />
  </div>
</template>

<style scoped>

</style>
