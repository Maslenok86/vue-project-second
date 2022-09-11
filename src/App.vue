<script setup>
import {RouterLink, RouterView} from "vue-router";
import Header from "./components/Header.vue";
import Promotion from "./components/Promotion.vue";
import Features from "./components/Features.vue";
import AboutArea from "./components/AboutArea.vue";
import Footer from "./components/Footer.vue";
import Developer from "./components/Developer.vue";
import Buying from "./components/Buying.vue";
</script>

<template>
  <Header/>
  <Promotion/>
  <Features/>
  <AboutArea/>
  <Buying/>
  <Developer/>
  <Footer/>
</template>

<style scoped>
</style>
