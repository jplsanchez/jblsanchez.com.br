<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <!-- <router-view/> -->
  <div class="container">
    <img class="profile-picture" src="/img/profile.jpg" />
    <div>
      <h1 style="font-size: x-large">Bem vindo ao site</h1>
      <h1 style="font-size: xx-large">jplsanchez.com.br</h1>
    </div>
  </div>
</template>

<style lang="scss">
@import "./global.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  // color: #2c3e50;
  color: $text;
}

.container {
  padding: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 100px;

  background-color: $backgroundAlt;
}

$profile-size: 150px;

.profile-picture {
  height: $profile-size;
  border-radius: $profile-size/2;
}
</style>
