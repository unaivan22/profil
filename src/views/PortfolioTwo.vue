<template>
    <div class="two main-content">
      <div class="left-content slideUp">
  
        <router-link to="/portfolio/one"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>
  
  
        <h1>UI DESIGN</h1>
        <p class="subtxt">I have determination to become experience front-end developer, creating responsive websites of a high quality.</p>
        <p class="subtxt">I love front-end development but my knowledge of multiple fields allows me to work on a project with the full scope in mind; simplifying the process of our working together and producing a more cohesive experience for your users.</p>
  
        <router-link to="/portfolio/three"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
      </div>
  
      <div class="right-content img2">
        
      </div>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue'
  
  export default {
    name: 'one',
    components: {
      HelloWorld
    }
  }
  </script>
  
  <style lang="scss" scoped>
  
    $page_color: #48b886;
  
    h1 {
      color: $page_color !important;
    }
  
    .img2 {
      background: url('../assets/2.jpg');
      background-size: cover;
      background-position: 50%;
  
      img {
        width: 50%;
      }
    }
  
  
  
  
  
  </style>