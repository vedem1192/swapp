<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
import ComingSoonView from './views/ComingSoonView.vue'
</script>

<template>
    <!-- <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
          <RouterLink to="/resume">Resume</RouterLink>
          <RouterLink to="/resume">Travel</RouterLink>
        </nav>
      </div>
    </header> -->
    <RouterView /> 
    <!-- <footer>
        blah
    </footer> -->
</template>

<style scoped>
header {
    position: sticky;
    top: 0;
    z-index: 100;
    height: 0;
}
</style>
