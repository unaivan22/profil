<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Junior Front End Developer</h1>

      <p class="subtxt">Hi my name is Ivan</p>
      <p class="subtxt">You can call me  with other name una. I’m a junior frontend developer from East Java, Indonesia. Please take a look around!</p>
      </div>

      <div class="right-content img1">
        <button><router-link to="/portfolio/one">Browse Me</router-link></button>
      </div>
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css?family=Ubuntu+Mono');


  .img1 {
    background: url('../assets/home.jpg');
  }

  p {
    /* font-family: 'Ubuntu Mono', monospace; */
    /* color: black; */
    /* font-weight: bold; */
  }

</style>