<template>
  <div class="secondary">
    <v-row class="home">
      <v-col class="pt-0 pb-0">
        <img
          src="https://images.pexels.com/photos/675764/pexels-photo-675764.jpeg"
        />
      </v-col>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>

<style scoped>
::v-deep img {
  height: 100vh!important;
  width: 100vw;
}
</style>