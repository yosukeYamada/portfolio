<template>
  <v-app>
    <Header />
    <v-content>
      <router-view />
    </v-content>
    <v-footer/>>
  </v-app>
</template>

<script>
import Header from "./components//common/Header";

export default {
  name: "App",

  components: {
    Header,
  },

  data: () => ({
    //
  }),
};
</script>
