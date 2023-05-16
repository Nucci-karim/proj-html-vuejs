<script>
import {store} from '../store';

export default{
  name: 'mainComp',
  components:{
    
  },
  data(){
    return{
      store,
      arrayInfo : [
            {
                classeIcon: 'fa-solid fa-link-slash',
                titolo: 'Strength & Conditioning',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!'
            },
            {
                classeIcon: 'fa-solid fa-bicycle',
                titolo: 'Fitness & Cardio',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!'
            },
            {
                classeIcon: 'fa-solid fa-lungs',
                titolo: 'Flexibility & rest',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!'
            },
            {
                classeIcon: 'fa-solid fa-heart-pulse',
                titolo: 'Health & Diet',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio ex atque aspernatur architecto quaerat fugiat doloremque, asperiores facere enim! Tempore, fugiat animi! Dolorum, cum!'
            },
        ],
        arrayResults: [
            {
                photo: 'src/assets/images/review_1-compressor.jpg',
                paragraph: '"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for. I love it!"',
                nome: '-Tara Smith'
            },
            {
                photo: 'src/assets/images/review_3-compressor-2.jpg',
                paragraph: '"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for. I love it!"',
                nome: '-Simon chel'
            },
            {
                photo: 'src/assets/images/review_2-compressor.jpg',
                paragraph: '"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for. I love it!"',
                nome: '-Jen Wirth'
            },
            {
                photo: 'src/assets/images/review_4-compressor-2.jpg',
                paragraph: '"The trainers at Avada Gym have helped me reach my fitness goals beyond anything i could of hoped for. I love it!"',
                nome: '-Jeff Glum'
            },
        ],
        arrayFacilities: [
            {
                image : '../src/assets/images/home-image1.jpg',
            },
            {
                image : '../src/assets/images/home-image2.jpg',
            },
            {
                image : '../src/assets/images/home-image3.jpg',
            },
            {
                image : '../src/assets/images/home-image4.jpg',
            },
            {
                image : '../src/assets/images/home-image54.jpg',
            },
            {
                image : '../src/assets/images/home-image6.jpg',
            },
        ],
        arrayTrainers:[
            {
                image: '../src/assets/images/trainer1-400x297.jpg',
                titlo:'Ann Baker',
                professione: 'Personal Trainer',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio',
            },
            {
                image: '../src/assets/images/trainer3-400x297.jpg',
                titlo:'Anne Warren',
                professione: 'Personal Trainer',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio',
            },
            {
                image: '../src/assets/images/trainer4-400x297.jpg',
                titlo:'Peter Rice',
                professione: 'Personal Trainer',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio',
            },
            
        ],
        arrayPerformance: [
            {
                image: '../src/assets/images/blog1-400X208.jpg',
                title: 'Train with free weights or your body weight',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
            {
                image: '../src/assets/images/blog6-400X400.jpg',
                title: 'Nutritional advice that will keep you training',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
            {
                image: '../src/assets/images/trainer4-400x297.jpg',
                title: 'Simple principles for your next workout',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
            {
                image: '../src/assets/images/blog4-400X289.jpg',
                title: "To be number one, train like you're number two",
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
            {
                image: '../src/assets/images/trainer3-400x297.jpg',
                title: 'Top five mistakes every gym member makes',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
            {
                image: '../src/assets/images/trainer1-400x297.jpg',
                title: 'The miths of shedding body fat explored',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, ad. Assumenda nisi, blanditiis illum optio'
            },
        ],
        

    }
  },
  created(){

  },
  methods: {
    
  }
}
</script>

<template>
  <section id="main">
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
            <div v-for="(elem, index) in arrayInfo" :key="index" class="col text-center">
                <i :class="elem.classeIcon" style="color: #ee6059;"></i>
                <h3>{{elem.titolo}}</h3>
                <img src="../assets/images/divider-x-red.png" alt="">
                <p>{{ elem.paragraph }}</p>
            </div>
        </div>
    </div>
    <!-- section -->
    <div id="results" class="p-3">
        <div class="container text-center column">
            <div>
                <h2>REAL WORD RESULTS</h2>
                <img class="my-3" src="../assets/images/divider-xx-red.png" alt="">
            </div>

            <div class="container d-flex flex-wrap justify-content-center">
                <div v-for="(elem, index) in arrayResults" :key="index" class="card m-3 col-4 p-1">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img :src="'../' + elem.photo" alt="">
                        </div>
                        <div class="col-md-8">
                        <div class="card-body">
                            <p class="card-text">{{elem.paragraph}}</p>
                            <p class="card-text"><small class="text-body-secondary">{{elem.nome}}</small></p>
                        </div>
                        </div>
                    </div>
                </div>
            </div>

            
        </div>
    </div>
    <!-- section -->
    <div id="facilities" class="p-4 text-center">
        <h2>HIGH PERFORMANCE FACILITIES</h2>
        <img src="../assets/images/divider-xx-red.png" alt="">
        <div class="d-flex flex-wrap justify-content-center align-items-center">
            <div v-for="(elem, index) in arrayFacilities" :key="index" class="col-3 m-2">
                <img :src="elem.image" alt="">
            </div>
        </div>
    </div>
    <!-- section -->
    <div id="quote-of-day" class="p-3 text-center d-flex justify-content-center align-items-center">
        <div class="col-8">
            <h3>"I fear not the man who has practiced 10,000 kicks once, but i fear the man who has practiced one kick 10,000 times"</h3>
            <span>BRUCE LEE - QUOTE OF THE DAY</span>
        </div>
    </div>
    <!-- section -->
    <div id="trainers" class="p-3 column">
        <div class="text-center">
            <h2>Meet our trainers</h2>
            <img src="../assets/images/divider-xx-red.png" alt="">
        </div>
        <div class="d-flex justify-content-center align-items-center">
            <div v-for="(elem,index) in arrayTrainers" :key="index" class="card m-2" style="width: 18rem;">
                <img :src="elem.image" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">{{elem.titlo}}</h5>
                    <h5 class="card-title">{{elem.professione}}</h5>
                    <p class="card-text my-2">{{ elem.paragraph }}</p>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-facebook-f" style="color: #ffffff;"></i>
                    </a>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-twitter" style="color: #ffffff;"></i>
                    </a>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="text-center">
            <a href="/" class="btn btn-outline-light col-3 my-3">View all trainers</a>
        </div>
    </div>
    <!-- section -->
    <div id="performance" class="p-3 column">
        <div class="text-center">
            <h2>PERFORMANCE NEWS</h2>
            <img src="../assets/images/divider-xx-red.png" alt="">
        </div>
        <div class=" d-flex flex-wrap justify-content-center align-items-center">
            <div v-for="(elem,index) in arrayPerformance" :key="index" class="card m-3 col-3" >
                <div id="search-on-img" class="position-relative">
                    <img :src="elem.image" class="card-img-top" alt="...">
                    <div id="to-hide" class="position-absolute top-50 start-50 translate-middle">
                        <i class="fa-solid fa-link"></i>
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </div>
                </div>
                <div class="card-body">
                    <h5 class="card-title">{{elem.title}}</h5>
                    <h5 class="card-title">{{elem.professione}}</h5>
                    <p class="card-text my-2">{{ elem.paragraph }}</p>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-facebook-f" style="color: #ffffff;"></i>
                    </a>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-twitter" style="color: #ffffff;"></i>
                    </a>
                    <a href="#" class="btn">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="text-center">
            <a href="/" class="btn btn-outline-light col-3 my-3">View all Articles</a>
        </div>
    </div>
    <!-- section -->
    <div id="achieve-goals" class="p-3 d-flex justify-content-center align-items-center">
        <div>
            <h2>Achieve your fitness goals</h2>
            <p>Flexible membering packages to suit all levels of athlete and achieve your fitness goals</p>
        </div>
        <div class="text-center">
            <a href="/" class="btn btn-outline-light m-3">Join us</a>
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
        min-height: 400px;
    }
    #sign-up{
        background-color: rgb(31 33 35);
        min-height: 400px;
        .btn{
            background-color: rgb(238 96 89);
        }
    }
    #info{
        background-image: url('../assets/images/gym_bkgd_bw-compressor.jpg');
        background-size: cover;
        background-position: top;
        background-repeat: no-repeat;
        min-height: 500px;
        i{
            font-size: 50px;
            border: 1px solid rgb(238 96 89);
            padding: 1.25rem 1rem;
            border-radius: 100%;
        }
    }

    #results{
        background-color: rgb(37 41 43);
        min-height: 500px;
        .card{
            background-color: rgb(31 33 35);
            
        }
    }

    #facilities{
        background-color: rgb(37 41 43);
        min-height: 500px;
        div{
            img{
                width: 94%;
            }

        }
    }

    #quote-of-day{
        background-image: url('../assets/images/home-testimonial-bg.jpg');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        min-height: 400px;
    }

    #trainers{
        background-color: rgb(31 33 35);
        height: 110%;
        .card{
            background-color: rgb(37 41 43);
            p{
                color: rgb(169 169 169);
            }
        }
    }

    #performance{
        background-color: rgb(37 41 43);
        min-height: 100%;
        #search-on-img{
            #to-hide{
                display: none;
                i{
                    margin: 0 0.5rem;
                }
            }
            &:hover{
                #to-hide{
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    background-color: rgba(213, 98, 95, 0.8);
                    width: 100%;
                    height: 100%;
                }
            }
        }
        .card{
            background-color: rgb(31 33 35);
            p{
                color: rgb(169 169 169);
            }
        }
    }

    #achieve-goals{
        min-height: 200px;
        background-image: url('../assets/images/home-parallax.jpg');
        background-size: cover;
        background-position: 50% 20%;
        background-repeat: no-repeat;
    }
}
</style>
