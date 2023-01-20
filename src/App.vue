<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'Vite DC Comics',
  components: { AppHeader }
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

/* GENERICS */

body {
  font-family: sans-serif;
  min-height: 100vh;
}

img {
  max-width: 100%;
  height: auto;
}

a {
  text-decoration: none;
}

ul li {
  list-style: none;
}

/* UTILS */

.container {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
