<template>
  <div class="home">
    <HeroSection />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import HeroSection from "@/components/Home/Hero.vue";
export default Vue.extend({
  name: "Home",

  components: {
    HeroSection,
  },
});
</script>
