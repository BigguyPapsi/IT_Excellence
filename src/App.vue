<template>
  <v-app>
    <v-main>
      <Home />
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Home from "./views/index.vue";

export default {
  name: "App",
  Home: {},
};
</script>

<style scoped></style>
