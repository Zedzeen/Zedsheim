<template>
  <div class="hero">
    <v-parallax dark src="@/assets/sweden (2).svg">
      <v-row align="center" justify="center">
        <v-container ma-0 pa-0>
          <v-col class="text-left" cols="12">
            <h1 class="display-4 font-weight-bold mb-4">👋 Hi, I'm Zedzee!</h1>
            <p class="text--secondary"></p>
          </v-col>
        </v-container>
      </v-row>
    </v-parallax>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style scoped>
div.v-parallax {
  height: 100vh !important;
}

.hero {
  position: absolute;
  width: 100vw;
  height: 100vh;
  top: 0;
}
</style>
