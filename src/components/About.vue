<script setup>
import TheShowMenu from '../partials/Menu.vue'
import TheSidebar from '../partials/Sidebar.vue'
</script>
<template>
  <TheSidebar/>
    <div class="main-content">
        <TheShowMenu/>
        <article class="about  active" data-page="about">
  
          <header>
            <h2 class="h2 article-title">About me</h2>
          </header>
  
          <section class="about-text">
            <p>
              Hi, let me introduce myself, my name is Andre Tri Ramadaana. I am a vocational high school (SMK) graduate who has just graduated and I am continuing my education at the University of North Sumatra majoring in Informatics Engineering. Now I am studying to become a Fullstack Web Developer.
            </p>
          </section>
   
  
          <section class="service">
  
            <h3 class="h3 service-title">What i'm doing</h3>
  
            <ul class="service-list">
  
              <li class="service-item">
  
                <div class="service-icon-box">
                  <img src="../assets/img/icon-dev.svg" alt="Web development icon" width="40">
                </div>
  
                <div class="service-content-box">
                  <h4 class="h4 service-item-title">Web development</h4>
  
                  <p class="service-item-text">
                    Build responsive and dynamic websites using html, css, javascript, jquery and php
                  </p>
                </div>
  
              </li>
  
              <li class="service-item">
  
                <div class="service-icon-box">
                  <img src="../assets/img/icon-app.svg" alt="mobile app icon" width="40">
                </div>
  
                <div class="service-content-box">
                  <h4 class="h4 service-item-title">Design Graphic</h4>
  
                  <p class="service-item-text">
                    Make designs, especially printing using figma and canva.
                  </p>
                </div>
  
              </li>
  
            </ul>
  
          </section>
         
        </article>
         
    </div>
    
</template>