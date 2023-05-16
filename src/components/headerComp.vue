<script>
import {store} from '../store';

export default{
  name: 'headerComp',
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
  <section id="header" class="">
    <nav class="container row justify-content-around align-items-center">
        <div id="logo-nav" class="col-2">
            <a href="/home">
                <img src="../assets/images/gym_logo_1x.png" alt="logo">
            </a>
        </div>
        <div class="col-4">
            <ul class="d-flex">
                <li>
                    <a href="/home">Home</a>
                </li>
                <li>
                    <a href="/">About Us</a>
                </li>
                <li>
                    <a href="/">Facilities</a>
                </li>
                <li>
                    <a href="/">Membership</a>
                </li>
                <li>
                    <a href="/">Testimonials</a>
                </li>
                <li>
                    <a href="/">Blog</a>
                </li>
            </ul>
        </div>
    </nav>
    <div id="join-us" class="col-12 text-center">
        <div class="column">
            <h1><strong>NO PAIN NO GAIN</strong></h1>
            <p class="mb-4">Motivation is what gets you started. Habit is what keeps you doing</p>
            <a href="/join-us" class="btn btn-outline-light">Join Us Today</a>
        </div>
    </div>
  </section>
</template>

<style lang="scss">
#header{
    background-image: url(../assets/images/home-banner.jpg);
    background-size: cover;
    background-position: center top;
    background-repeat: no-repeat;
    min-height: 600px;
    nav{
        padding: 1rem 0;
        min-height: 10%;
        #logo-nav{
            img{
                width: 100%;
            }
        }
        ul{
            li{
                list-style: none;
                margin: 0 1rem;
                a{
                    text-decoration: none;
                    color: white;
                    &:hover{
                        color: rgb(205 85 79);
                    }
                }
            }
        }
    }
    #join-us{
        height: 80%;
        h1{
            font-size: 80px;
        }
    }

    
}
</style>
