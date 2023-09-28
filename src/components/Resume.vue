<script setup>
import TheShowMenu from '../partials/Menu.vue'
import TheSidebar from '../partials/Sidebar.vue'
</script>
<template>
    <TheSidebar/>
    <div class="main-content">
        <TheShowMenu/>
        <article class="resume active" data-page="resume">
  
          <header>
            <h2 class="h2 article-title">Resume</h2>
          </header>
  
          <section class="timeline">
  
            <div class="title-wrapper">
              <div class="icon-box">
                <ion-icon name="book-outline"></ion-icon>
              </div>
  
              <h3 class="h3">Education</h3>
            </div>
  
            <ol class="timeline-list">
  
              <li class="timeline-item">
  
                <h4 class="h4 timeline-item-title">Sumatera Utara University</h4>
  
                <span>2023 — Now</span>
  
                <p class="timeline-text">
                  During college I was active in class collaborations, took part in several competitions and IT training activities and worked part time and as a freelancer
                </p>
  
              </li>
  
              <li class=" timeline-item">
  
                <h4 class="h4 timeline-item-title">SMKN1 Stabat</h4>
  
                <span>2021 — 2023</span>
  
                <p class="timeline-text">
                  During school I was active in taking part in digital competitions
                </p>
  
              </li>
  
            </ol>
  
          </section>
  
          <section class="timeline">
  
            <div class="title-wrapper">
              <div class="icon-box">
                <ion-icon name="book-outline"></ion-icon>
              </div>
  
              <h3 class="h3">Experience</h3>
            </div>
  
            <ol class="timeline-list">
  
              <li class="timeline-item">
  
                <h4 class="h4 timeline-item-title">Freelance Customer Service  - Jagadhost</h4>
                <span>Aug 2023 - Now</span>
                <p class="timeline-text">
                  - Learn to serve, help and solve consumer problems<br>
                  - Create quality article content<br>
                  - Learn to communicate, and work together with a team<br>
                </p>
  
              </li>
  
              <li class="timeline-item">
  
                <h4 class="h4 timeline-item-title">Electronics Internship and Training - Cv Good Electronics</h4>
                <span>Sep 2022 - Nov 2022</span>
  
                <p class="timeline-text">
                  - Repair damaged TV components and replace TV spare parts<br>
                  - Repairing electronic equipment, such as blenders, irons, etc.<br>
                  - Analyze the occurrence of damage to electronic devices.
                </p>
  
              </li>
  
             
            </ol>
  
          </section>
  
          <section class="skill">
  
            <h3 class="h3 skills-title">My skills</h3>
  
            <ul class="skills-list content-card">
  
  
              <li class="skills-item">
  
                <div class="title-wrapper">
                  <h5 class="h5">Web Apps</h5>
                  <data value="70">70%</data>
                </div>
  
                <div class="skill-progress-bg">
                  <div class="skill-progress-fill" style="width: 70%;"></div>
                </div>
  
              </li>
  
              <li class="skills-item">
  
                <div class="title-wrapper">
                  <h5 class="h5">Graphic Design</h5>
                  <data value="60">60%</data>
                </div>
  
                <div class="skill-progress-bg">
                  <div class="skill-progress-fill" style="width: 80%;"></div>
                </div>
  
              </li>
  
              <li class="skills-item">
  
                <div class="title-wrapper">
                  <h5 class="h5">Microsoft Office</h5>
                  <data value="70">70%</data>
                </div>
  
                <div class="skill-progress-bg">
                  <div class="skill-progress-fill" style="width: 70%;"></div>
                </div>
  
              </li>
  
            </ul>
  
          </section>
  
        </article>
    </div>
</template>