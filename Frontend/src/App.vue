<!-- fichier central de l'qpplication Vue.-->

<template>
    <div id="app">
      <Navi></Navi>
      <router-view></router-view>
    </div>
</template>

<script>
import Navi from "./components/Navi";

export default {
    name: "App",
    components: {
      Navi
    }
}
</script>

<style>
  body {
    background: black;
    background: linear-gradient(90deg, rgb(7, 7, 7) 0%, rgb(59, 61, 63) 100%);
  }
</style>
