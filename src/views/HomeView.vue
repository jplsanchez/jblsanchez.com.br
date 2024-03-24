<template>
  <v-container
    class="d-flex align-center justify-center mt-10"
    :class="mobile && 'flex-column'"
  >
    <div class="ma-10">
      <v-img src="/img/profile.jpg" class="circle-image" />
    </div>

    <div class="d-flex flex-column align-center justify-center">
      <h2 class="pa-4">Bem vindo ao site</h2>
      <v-sheet class="strong pa-4" rounded> <h1>jplsanchez.com.br</h1> </v-sheet>
    </div>
  </v-container>
</template>

<script setup lang="ts">
import { useDisplay } from "vuetify";

const { mobile } = useDisplay();
</script>

<style lang="scss">
$profile-size: 150px;

.circle-image {
  height: $profile-size;
  width: $profile-size;
  border-radius: $profile-size/2;
}
</style>
