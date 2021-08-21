<template>
  <v-app>
    <Navbar />
    <v-main style="transform: translateY(-64px)">
      <transition name="fade">
        <router-view />
      </transition>
    </v-main>
    <Footer />
    <div id="projects"></div>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Footer from "@/components/Footer.vue";
import Navbar from "@/components/Navbar.vue";

export default Vue.extend({
  name: "App",

  data: () => ({
    //
  }),
  components: {
    Footer,
    Navbar,
  },
});
</script>

<style>
html {
  scroll-behavior: smooth;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}

.container {
  max-width: 1400px;
}
</style>
