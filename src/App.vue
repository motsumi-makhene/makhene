<template>
  <v-app>
    <v-app-bar
      app
      color="#222"
      dark
    >
      <div class="d-flex align-center">
        <h1>MAKHENE</h1>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        to="/login"
        text
      >
        <span class="mr-2">Login</span>
        <v-icon>mdi-login</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
   
  },

  data: () => ({
    //
  }),
};
</script>
