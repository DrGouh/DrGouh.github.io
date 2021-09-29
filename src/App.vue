<template>
  <Auth></Auth>
</template>

<script>
import Auth from './components/Auth.vue'

export default {
  name: 'App',
  components: {
    Auth
  }
}
</script>

<style>

@font-face {
  font-family: "ana";
  src: local("ana"),   url(./fonts/ana.ttf) format("truetype");}

  @font-face {
  font-family: "inna";
  src: local("inna"),   url(./fonts/inna.ttf) format("truetype");}

    @font-face {
  font-family: "sl";
  src: local("sl"),   url(./fonts/sl.ttf) format("truetype");}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
