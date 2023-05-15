<script>
import axios from 'axios';
import {store} from './store';
import headerComp from './components/headerComp.vue';
import mainComp from './components/mainComp.vue';
import footerComp from './components/footerComp.vue';

export default{
  name: 'app',
  components:{
    headerComp,
    mainComp,
    footerComp,
  },
  data(){
    return{
      store
    }
  },
  created(){

  },
  methods: {

  }
}
</script>

<template>
  <div id="tutto">
    <headerComp/>
    <mainComp/>
    <footerComp/>
  </div>
  
  
</template>

<style lang="scss">
@use './style/main.scss' as *;

#tutto{
height: 100vh;
}


</style>
