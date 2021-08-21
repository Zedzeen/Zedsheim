<template>
  <v-footer color="transparent lighten-1" padless>
    <v-row justify="center" no-gutters>
      <v-btn color="white" text rounded class="my-2" href="/"> Home </v-btn>
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        text
        rounded
        class="my-2"
        :to="link"
      >
        {{ link }}
      </v-btn>
      <v-btn
        color="white"
        text
        rounded
        class="my-2"
        href="https://cdn.zedsheim.com/"
      >
        CDN
      </v-btn>
      <v-col class="transparent py-4 text-center white--text" cols="12">
        {{ new Date().getFullYear() }} — <strong>Zedzee</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  data: () => ({
    links: ["Projects", "Write-ups", "Blog"],
  }),
});
</script>

<style scoped></style>
