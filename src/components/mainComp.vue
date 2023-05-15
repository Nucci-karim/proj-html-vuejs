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
    <!-- section -->
    <div id="world-class" class="col-12 text-center column position-relative ">
        <div class="position-absolute top-50 start-50 translate-middle">
            <h2>WORLD CLASS Fitness</h2>
            <img src="../assets/images/divider-xx-red.png" alt="">
            <p>
                At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped
                to help you reach your hoals of healty and fit lifestyle.
            </p>
        </div>
    </div>
    <!-- section -->
    <div id="sign-up" class="col-12 d-flex justify-content-center align-items-center">
        <img src="../assets/images/home_img-compressor-400x222.jpg" alt="">
        <div class="row col-4 mx-2">
            <h3>Sign Up for A Free Training Session!</h3>
            <label class="form-label p-0">Name:</label>
            <input type="text" class="form-control p-0">
            <label for="exampleFormControlInput1" class="form-label p-0">Email address:</label>
            <input type="email" class="form-control p-0" id="exampleFormControlInput1" placeholder="name@example.com">
            <button type="button" class="btn my-4">START NOW!</button>
        </div>
    </div>
    <!-- section -->
    <div id="info" class="p-3 d-flex justify-content-center align-items-center">
        <div class="container d-flex">
            <div class="col text-center">
                <i class="fa-solid fa-link-slash" style="color: #ee6059;"></i>
                <h3>Strength & Conditioning</h3>
                <img src="../assets/images/divider-x-red.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!</p>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-bicycle" style="color: #ee6059;"></i>
                <h3>Strength & Conditioning</h3>
                <img src="../assets/images/divider-x-red.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!</p>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-lungs" style="color: #ee6059;"></i>
                <h3>Strength & Conditioning</h3>
                <img src="../assets/images/divider-x-red.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!</p>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-heart-pulse" style="color: #ee6059;"></i>
                <h3>Strength & Conditioning</h3>
                <img src="../assets/images/divider-x-red.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!</p>
            </div>
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
    #sign-up{
        background-color: rgb(31 33 35);
        height: 80%;
        .btn{
            background-color: rgb(238 96 89);
        }
    }
    #info{
        background-image: url('../assets/images/gym_bkgd_bw-compressor.jpg');
        background-size: cover;
        background-position: top;
        background-repeat: no-repeat;
        height: 90%;
        i{
            font-size: 50px;
            border: 1px solid rgb(238 96 89);
            padding: 1.25rem 1rem;
            border-radius: 100%;
        }
    }
}
</style>
