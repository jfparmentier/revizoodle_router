<template>
  <div id="app">
    <router-view/>
    <Footer />
  </div>
</template>

<script>
import Footer from "@/views/Footer";
export default {
  name: 'App',
  components: {Footer}
}

</script>

<style>
@import "assets/styles/normalize.css";
@import "assets/styles/skeleton.css";
@import "assets/styles/extensionBoutons.css";
@import "assets/styles/boutonsAdele.css";
</style>
