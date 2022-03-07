<template>
  <v-app>
    <v-app-bar
      id="nav"
      flat
      height="100"
      dense
      absolute
      color="rgba(49, 49, 49, 0.19)"
    >
      <v-row class="py-2 px-6">
        <v-col
          cols="12"
          class="d-flex align-center justify-center"
        >
          <router-link to="/" class="mr-6 title font-weight-light">
            HOME
          </router-link>
          <router-link to="/about" class="mr-6 title font-weight-light">
            ABOUT
          </router-link>
          <router-link to="/plat" class="mr-6 title font-weight-light">
            LOTS
          </router-link>
          <router-link
            to="/login"
            class="title font-weight-light"
          >
            LOGIN
          </router-link>
        </v-col>
      </v-row>
    </v-app-bar>

    <v-main>
      <router-view class="pt-3" />
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: "App",
};
</script>

<style lang="scss">
#nav a {
  text-decoration: none;
  color: white !important;
}
</style>
