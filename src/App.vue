<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import TopNav from './components/TopNav.vue'
import Lobby from './views/Lobby.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header />
  <TopNav />
  <!--RouterView /-->
  <Lobby />
  <Footer />
</template>
