<template>
  <div id="nav">
    <v-app-bar app>
      <div class="d-flex align-center"></div>
      <v-btn text>
        <router-link to="/">
          <span class="mr-2">Poetster Logo</span></router-link
        >
      </v-btn>
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
