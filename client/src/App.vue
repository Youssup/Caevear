<script setup lang="ts">
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <header>
    <nav>
      <Navbar />
    </nav>
  </header>
  <main>
    <RouterView />
  </main>
  <Footer />
</template>

<style scoped></style>