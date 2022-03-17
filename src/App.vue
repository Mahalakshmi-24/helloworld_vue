<template>

  <TheHeader :title="pageHeader" :description="pageDescription" />

  <TheFooter />

</template>

<script setup>
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'


const pageHeader ='Home page';
const pageDescription ='landing page of website';


</script>

<style>

</style>
