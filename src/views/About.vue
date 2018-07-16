<template>
    <div class="about main-content">
      <div class="left-content">
        <h2>About me</h2>
        <img src="../assets/pp.jpeg" alt="pp" class="responsive">
        
      </div>
      <div class="right-content">
        <p class="subtxt" style="margin-top: -20px;">I design, prototyping, code, and work with teams.</p>
        <p> <h3>mySkills</h3> 
          <ul>
            <li>Photoshop / Krita</li>
            <li>Illustrator</li>
            <li>Premiere Pro</li>
            <li>XD</li>
            <li>HTML & CSS</li>
            <li>Bootstrap & Materializecss</li>
            <li>Javascript & JQuery</li>
            <li>Vuejs</li>
            <li>Git</li>
            <li>Basic Networking (routing, subnetting, firewall, proxy)</li>
            <li>Linux {Ubuntu(XFCE), Opensuse(KDE)}</li>
          </ul></p>
        <!-- <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi distinctio amet id recusandae, minima voluptates quo fugit beatae nihil vitae, natus alias debitis placeat. Veniam consequatur autem ullam error adipisci?</p> -->
        <button><router-link to="/portfolio/one">Look at my work</router-link></button>
        <ul class="target">
            <a href="https://www.facebook.com/dean.n.indra" target="_blank">facebook</a>
            <a href="https://www.github.com/unaivan22" target="_blank">github</a>
            <a href="https://www.codepen.io/unaivan" target="_blank">codepen</a>
            <a href="https://www.instagram.com/dinivan.nendra" target="_blank">instagram</a>
        </ul>
      </div>
    </div>
  </template>
  
  <style lang="scss" scoped>
  
    .left-content {
      background-color: #d7d7d7;
    }
  
    .right-content {
      background: #fff;
      padding: 50px;
      margin-top: 80px;
      display: block;
    }

    ul {
      margin-left:-40px;
      list-style-type: none;
    }

    h2 {
      /* margin-top: -20px; */
      color: #fff;
    }

    .responsive {
    width: 100%;
    max-width: 300px;
    height: auto;
    }

    img  {
      margin: auto;
      height: 100px;
      width: 100px;
      min-width: 50%;
      border-radius: 20px;
    }

    .target a {
      margin-top: 20px;
      padding-right: 20px;
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
  
    .subtxt {
      font-size: 1.5em;
      margin-top: 30px;
    }
  
  </style>