<template>
  <div class="app">
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Righteous&display=swap');
.app {
  min-height: 100vh;
  min-width: 300px;
  background-color: #DCF763;
  font-family: 'Righteous', cursive;
}

nav a.router-link-exact-active {
  color: black;
}
</style>
