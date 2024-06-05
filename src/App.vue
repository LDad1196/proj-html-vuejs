<script>
  import AppHeader from './components/AppHeader.vue';
  import appMainUno from './components/appMainUno.vue';
  import AppMain4 from './components/AppMain4.vue';
  import AppMain5 from './components/AppMain5.vue';
  import AppMain6 from './components/AppMain6.vue';
  import store from './data/store.js';

  export default {
      components:{
        AppHeader,
        appMainUno,
        AppMain4,
        AppMain5,
        AppMain6,
      },
  

    data (){
      return {
        store,
      }
    },

    created (){

    },

    mounted(){

    }
  }
</script>

<template>
  <AppHeader />
  <appMainUno/>
  <AppMain4 />
  <AppMain5 />
  <AppMain6 />
</template>

<style scoped>

</style>
