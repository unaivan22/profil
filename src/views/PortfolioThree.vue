<template>
    <div class="three main-content">
      <div class="left-content slideUp">
  
        <router-link to="/portfolio/two"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>
  
        <h1>SLICING</h1>
  
        <p class="subtxt">I loving create responsive websites that allow the user to experience your website in the best and most appropriate way suited to the device they are using. Cross browser compatibility is ensured by using feature detection so older browsers still in use today provide a solid experience, whilst modern browsers can go the next step and enhance a user’s time spent on your site.</p>
        <!-- <p class="subtxt">Writing semantic markup that is documented and easy to read means it can be maintained and scaled in the future, and allows co-workers to quickly work with it.</p> -->
        <button><router-link to="/about">About</router-link></button>
      </div>
  
      <div class="right-content img2">
  
      </div>
    </div>
  </template>
  
  <script>
  
  export default {
    name: 'three'
  }
  </script>
  
  <style lang="scss" scoped>
  
    $page_color: #5487a8;
  
    h1 {
      color: $page_color !important;
    }
  
    .img2 {
      background: url('../assets/3.jpg');
      background-size: cover;
      background-position: 50%;
  
      img {
        width: 50%;
      }
    }

    button {
      margin-top: 20px;
      margin-left: auto;
      background: none;
      padding: 15px 20px;
      font-size: 1.7em;
      outline: 0;
      border: 1px solid #017FAF;
      color: lightblue;
      text-transform: uppercase;
      font-family: 'Montserrat';
      cursor: pointer;
    }

  </style>