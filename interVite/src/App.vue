<template>
<div>
  <Header></Header>
  <HelloWorld msg="Hello Vue 3 + Vite" />
  <Footer/>
</div>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
body{
  padding: 20px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
</style>
