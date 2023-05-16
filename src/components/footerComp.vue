<script>
import {store} from '../store';

export default{
  name: 'footerComp',
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
  <section id="footer">
    <!-- section -->
    <div id="about-us" class="p-3 d-flex justify-content-center align-items-center">
      <div>
        <ul>
          <h3>Come Find Us</h3>
          <li>12345 North main street</li>
          <li>New York, NY555555</li>
          <li>Phone: 1.800.555.6789</li>
          <li>email: info@your-domain.com</li>
        </ul>
      </div>

      <div class="">
        <ul>
          <h3 class="">Come Find Us</h3>
          <li class="">
            <i class="fa-solid fa-angle-right"></i> 
            Train with free weights or your body weight
            <hr>
          </li>
          <li class="list-group-item">
            <i class="fa-solid fa-angle-right"></i> 
            Nutritional advice that will keep you training
            <hr>
          </li>
        </ul>
      </div>

      <div class="">
        <ul>
          <h3 class="">Opening Times</h3>
          <li class="">
            Weekdays Monday - Friday
            <h6>09:00 - 19:00</h6>
          </li>
          <li class="list-group-item">
            Weekdays Saturday - Sunday 
            <h6>09:00 - 21:00</h6>
          </li>
        </ul>
      </div>

      <div class="mx-4">
        <img src="../assets/images/gym_ad-compressor-200x133.jpg" alt="">
      </div>
      
    </div>
    <!-- section -->
    <div id="copyright" class="p-3 d-flex justify-content-center align-items-center">
      <i class="fa-regular fa-copyright"></i>
      <span>Copyright 2012 - 2020</span>
      <span>|</span>
      <span>Avada Theme By Theme Function</span>
      <span>|</span>
      <span>All right Reserved</span>
      <span>|</span>
      <span>Powered by WordPress</span>
    </div>
  </section>
</template>

<style lang="scss">
#footer{
    min-height: 400px;
    .card, .list-group-item, .list-group{
          background-color: rgb(31 33 35);
          color: white;
        }
    #about-us{
      height: 300px;
      background-color: rgb(31 33 35);
      h3{
        color: rgb(112 123 128);
      }
      ul{
        list-style: none;
        h6{
          color: rgb(74 80 83);
        }
      }
    }
    #copyright{
      height: 100px;
      background-color: rgb(26 28 30);
      span{
        margin: 0 1rem;
      }
    }
}
</style>
