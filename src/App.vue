<script>
export default {
  mounted() {
    let self = this;
    document.addEventListener("mousemove", function (e) {
      self.$refs.pointer_0.style.left = e.pageX + "px";
      self.$refs.pointer_0.style.top = e.pageY + "px";
      self.$refs.pointer_1.style.left = e.pageX + "px";
      self.$refs.pointer_1.style.top = e.pageY + "px";
    });
  }
}
</script>
<script setup>

import Header from './components/Header.vue';
import HomeView from './views/HomeView.vue';
import AboutView from './views/AboutView.vue';
import SkillsView from './views/SkillsView.vue';
import ContactView from './views/ContactsView.vue';
import ProjectsView from './views/ProjectsView.vue';
import Footer from './components/Footer.vue';
import './scss/styles.scss';
import './scss/stars.scss';


</script>

<template>
  <div class="cursor outer" ref="pointer_0"></div>
  <div class="cursor inner" ref="pointer_1"></div>
  <div class="stars"></div>
  <div class="stars2"></div>
  <div class="stars3"></div>
  <Header />
  <HomeView />
  <AboutView />

  <SkillsView />
  <div class="stars"></div>
  <div class="stars2"></div>
  <div class="stars3"></div>

  <ProjectsView />

  <ContactView />
  <Footer />
</template>






