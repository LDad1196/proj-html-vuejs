<script>
  import AppHeader from './components/AppHeader.vue';
  import store from './data/store.js';

  export default {
      components:{
        AppHeader,
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
</template>

<style scoped>

</style>
