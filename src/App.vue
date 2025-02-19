<template>
  <div> 
    <PreLoader />
    <Header />
    <RouterView />
    <Footer />
  </div>
</template>

<script setup>
import PreLoader from './components/PreLoader.vue';
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import { RouterLink, RouterView } from 'vue-router'

</script>
