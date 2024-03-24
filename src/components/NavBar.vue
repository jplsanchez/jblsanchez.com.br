<template>
  <v-app-bar height="100" class="pa-2" :class="!mobile && ' px-10'">
    <v-img src="/img/logo-inv.png" max-width="100" />
    <v-spacer />
    <v-btn
      target="_blank"
      href="https://linkedin.com/in/jplsanchez"
      class="mx-3"
      size="50"
    >
      <v-icon icon="mdi-linkedin" size="50" />
    </v-btn>
    <v-btn target="_blank" href="https://github.com/jplsanchez" class="mx-3" size="50">
      <v-icon icon="mdi-github" size="50" />
    </v-btn>
  </v-app-bar>
</template>

<script setup lang="ts">
import { useDisplay } from "vuetify";

const { mobile } = useDisplay();
</script>
