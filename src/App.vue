<template>
  <div id="app">
    <br><br>
    <img  v-scrollanim id="image" height="80" width="300" src="./assets/shardalogo.png"/>
    <br><br>
    <h3 v-scrollanim>SCHOOL OF ENGINEERING AND TECHNOLOGY</h3> <br>
    <h3 v-scrollanim>PRESENTS</h3> <br>
    <p v-scrollanim><img height="70" width="70" src="./assets/books.png"/> LEARNSHALA</p> 
    <a href="#" v-scrollanim>Where learning never stops!</a><br><br>
    <button v-scrollanim>Enter Learnshala</button>
    <br><br>
    <div id="info">
      <AboutUs/>
      <br><br>
    </div>
    <div id="learn">
      <Learnshala/>
    </div>
  </div>
</template>

<script>
import AboutUs from '@/components/AboutUs.vue'
import Learnshala from '@/components/Learnshala.vue'

export default {
  name: 'app',
  components: {
    AboutUs,
    Learnshala
  }
  
}
</script>

<style lang="scss">
#app {
    font-family: 'Anton', Arial, Helvetica, sans-serif;
    font-size: 1rem;
    letter-spacing: 1px;
    color: #322F42;
    width: 100%;
    min-height: 100vh;
    background: #0627F0;
    background-size: cover;
    overflow: hidden;
    text-align: center;
  }
  #app h3{
    color: #fff;
  }
  #app p{
    color: #fff;
    font-size: 30px;
  }
  #app a{
    color: #fff;
  }
  #app button{
    background: #fff;
    border: 2px solid white;
    border-radius: 4px;
  }
  #app #image{
    background: white;
  }
  #info{
    background: white;
    color: black;
    text-align: center;
  }
  #info h3{
    color: black;
  }
  #info h1{
    font-style: bold;
  }
  #learn {
    background: violet;
    color: blue;
  }
  #learn p{
    color: black;
  }
  #info button{
    background: blue;
    color: white;
    font-size: 30px;
    border-radius: 15px;
  }
  .before-enter {
    opacity: 0;
    transform: translateX(100px);
    transition: all 1s cubic-bezier(.41,.01,.57,1.61);
  }
  .enter {
    opacity: 1;
    transform: translateX(0px);
  }
</style>
