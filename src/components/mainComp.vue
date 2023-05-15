<script>
import {store} from '../store';

export default{
  name: 'mainComp',
  components:{
    
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
  <section id="main" class="">
    <div id="world-class" class="col-12 text-center column position-relative ">
        <div class="position-absolute top-50 start-50 translate-middle">
            <h2>WORLD CLASS Fitness</h2>
            <img src="../assets/images/divider-xx-red.png" alt="">
            <p>
                At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped <br>
                to help you reach your hoals of healty and fit lifestyle.
            </p>
        </div>
    </div>

  </section>
</template>

<style lang="scss">
#main{
    height: 80%;
    #world-class{
        // background-image: url('../assets/images/chat-svgrepo-com.png');
        // background-size: cover;
        // background-position: center bottom;
        // background-repeat: no-repeat;
        background-color: rgb(37 41 43);
        padding: 2rem 0;
        height: 80%;
    }
}
</style>
