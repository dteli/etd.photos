<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
    <router-view/>
    <div id="main-spacer"></div>
    <Footer/>
  </div>
</template>

<script lang="ts">
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Footer
  }
}
</script>

<style lang="scss">
@use 'css/vars' as v;
@use 'css/exts' as x;
@import url('https://fonts.googleapis.com/css2?family=Overpass:ital,wght@0,400;0,700;1,400;1,700&family=Volkhov:ital,wght@0,400;0,700;1,400;1,700&display=swap');

* {
  box-sizing: border-box;

}

html {
  font-size: 12px;
}

body {
  margin: 0;

  font-family: v.$f-body;
  h1,h2,h3,h4,h5,h6 {
    font-family: v.$f-title;
  }
}

#app {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  //text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  min-height: 40px;
  margin: 0;
  flex-grow: 0;
  font-size: 1.6rem;
  background-color: #333;
  color: v.$c-white;

  @extend %link-colors;
}

div#main-spacer {
  flex-grow: 1;
}

div.main-div {
  margin-left: 4rem;
  margin-top: 4rem;
  flex-grow: 0;
}
</style>
