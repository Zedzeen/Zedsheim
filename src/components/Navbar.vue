<template>
  <v-app-bar app flat dark class="transparent">
    <v-spacer></v-spacer>
    <div v-if="$router.currentRoute.name == 'Home'">
    <v-btn href="#projects" text> Projects </v-btn>
    <v-btn href="#write-ups" text> Write-ups </v-btn>
    </div>

    <v-btn href="https://github.com/zedzeen" target="_blank" rounded light>
      <span class="mr-2">github</span>
      <v-icon right>mdi-open-in-new</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style scoped></style>
