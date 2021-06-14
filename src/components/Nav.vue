<template>
  <div id="nav">
    <v-app-bar app>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>
      <v-spacer></v-spacer>

      <v-btn text>
        <router-link to="/login">
          <span class="mr-2">Manage Poems</span></router-link
        >
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn text>
        <router-link to="/login"> <span class="mr-2">Login</span></router-link>
      </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
a {
  text-decoration: none;
  color: #fff !important;
}
</style>
