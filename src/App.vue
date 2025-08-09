<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import TopNav from './components/TopNav.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header />
  <TopNav />
  <RouterView />
  <Footer />
</template>
