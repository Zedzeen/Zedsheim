<template>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
        <v-spacer />
      <v-col class="col-6">
        <h1 class="display-4">404 Not Found!</h1>
        <p class="subheader">
          Looks what you are trying to view is not available ¯\_(ツ)_/¯
        </p>
        <hr>
        <div style="float: right; margin-top:1rem">
        <v-btn text href="/">To Homepage</v-btn>
        <v-btn outlined @click="$router.back()">Go Back</v-btn>
        </div>
      </v-col>
      <v-spacer />
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style scoped>

</style>
