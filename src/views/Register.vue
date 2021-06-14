<template>
  <div>
    <v-form v-model="valid">
      <v-container>
        <v-row>
          <v-col cols="12" md="5" offset-md="3">
            <v-text-field
              v-model="email"
              :rules="emailRules"
              label="E-mail"
              required
            ></v-text-field>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" md="5" offset-md="3">
            <v-text-field
              v-model="password"
              :counter="10"
              label="Pen name"
              required
            ></v-text-field>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" md="5" offset-md="3">
            <v-text-field
              v-model="password"
              type="password"
              :counter="10"
              label="Password"
              required
            ></v-text-field>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" md="5" offset-md="3">
            <v-text-field
              v-model="password"
              type="password"
              :counter="10"
              label="Confirm Password"
              required
            ></v-text-field>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="12" md="5" offset-md="5">
            <v-btn :disabled="!valid" class="mr-4" @click="validate">
              Log In
            </v-btn>
          </v-col>
        </v-row>

        <router-link to="/login">
          <span class="mt-8 mr-16"
            >Already have an account? Login</span
          ></router-link
        >
      </v-container>
    </v-form>
  </div>
</template>

<script>
export default {
  name: "Register",

  components: {},
  data: () => ({}),
};
</script>
<style scoped>
span {
  display: block;
  text-align: center;
}
a {
  color: white !important;
}
</style>
