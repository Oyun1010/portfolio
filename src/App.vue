<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue';
import HomeView from './views/HomeView.vue';
import AboutView from './views/AboutView.vue';
import SkillsView from './views/SkillsView.vue';
import Footer from './components/Footer.vue';
import './scss/styles.scss'
</script>

<template>
  <Header />
  <HomeView />
  <AboutView />
  <SkillsView />
  <Footer />
</template>




