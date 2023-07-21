<template>
  <v-app>
    <v-main>
      <SevenVuetify />
    </v-main>
  </v-app>
</template>

<script>
import SevenVuetify from "./components/SevenVuetify.vue";

export default {
  name: "App",

  components: {
    SevenVuetify,
  },

  data: () => ({
    //
  }),
};
</script>
