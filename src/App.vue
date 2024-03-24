<template>
  <v-layout class="rounded rounded-md">
    <NavBar />
    <v-main>
      <router-view />
    </v-main>
  </v-layout>
</template>

<script setup lang="ts">
import NavBar from "./components/NavBar.vue";
</script>
