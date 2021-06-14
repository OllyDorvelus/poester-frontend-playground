<template>
  <div id="nav">
    <div class="center examplex">
      <vs-navbar square center-collapsed v-model="active">
        <template #left>
          <img src="/logos/logo-vuesax-logotipo-vuesax-png-4.png" alt="" />
        </template>
        <vs-navbar-item>
          <router-link to="/">Home</router-link>
        </vs-navbar-item>
        <vs-navbar-item>
          <router-link to="/">Poem Manager</router-link>
        </vs-navbar-item>
        <template #right>
          <vs-button color="#fff" flat>Login</vs-button>
          <vs-button color="#fff" border>Get Started</vs-button>
        </template>
      </vs-navbar>
    </div>
    <router-view />
    <vs-button> Active </vs-button>
    <div class="div1 theme-container">HWLLL</div>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
// .div1 {
//   height: 1000px;
// }
</style>
