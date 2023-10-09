<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';
export default {
  components:{
    'app-title':AppTitle,
    'jumbotron':AppHero,
  }
}
</script> 
<template>
  <app-title/>
  <jumbotron/>
</template>

<style>

</style>