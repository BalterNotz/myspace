<script lang="ts" setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Top from './components/Top.vue';
import HelloWorldVue from './components/HelloWorld.vue';
import FooterVue from './components/Footer.vue';
</script>

<template>
  <Top></Top>
  <HelloWorldVue msg="Hello Vue 3 + Vite" />
  <FooterVue></FooterVue>
</template>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: grid;
  height: 100%;
  grid-template-columns: auto;
  grid-template-rows: auto auto auto;
}
</style>
