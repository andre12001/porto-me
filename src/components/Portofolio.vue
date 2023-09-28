<script setup>
import TheShowMenu from '../partials/Menu.vue'
import TheSidebar from '../partials/Sidebar.vue'
</script>
<template>
    <TheSidebar/>
    <div class="main-content">
        <TheShowMenu/>
        <article class="portfolio active" data-page="portfolio">

            <header>
              <h2 class="h2 article-title">Portfolio</h2>
            </header>
    
            <section class="projects">
    
              <ul class="filter-list">
    
                <li class="filter-item">
                  <button class="active" data-filter-btn>All</button>
                </li>
    
              </ul>
     
    
              <ul class="project-list">
    
                <li class="project-item  active" data-filter-item data-category="web applications">
                  <a href="https://atranathemes.github.io/" target="_blank">
    
                    <figure class="project-img">
                      <div class="project-item-icon-box">
                        <ion-icon name="eye-outline"></ion-icon>
                      </div>
    
                      <img src="../assets/img/atrana.jpg" alt="sendangproject" loading="lazy" height="50px">
                    </figure>
    
                    <h3 class="project-title">Dashboard Admin Atrana</h3>
    
                    <p class="project-category">Web Themes</p>
    
                  </a>
                </li>
    
                <li class="project-item  active" data-filter-item data-category="web applications">
                  <a href="https://andre12001.github.io/" target="_blank">
    
                    <figure class="project-img">
                      <div class="project-item-icon-box">
                        <ion-icon name="eye-outline"></ion-icon>
                      </div>
    
                      <img src="../assets/img/dwadmin.jpg" alt="perpuskita" loading="lazy" height="50px">
                    </figure>
    
                    <h3 class="project-title">Dashboard Admin Atrana</h3>
    
                    <p class="project-category">Web Themes</p>
    
                  </a>
                </li>
    
               
    
              </ul>
    
            </section>
    
          </article>

    </div>
</template>