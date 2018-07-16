<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Prototyping</h1>

      <p class="subtxt">I started by designing a prototype first. I am used to using Photoshop, Illustrator, or XD </p>
      
      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>

      <div class="right-content img2">
        <!-- <img src="../assets/1.jpg">   -->
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
    background: url('../assets/1.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }


</style>