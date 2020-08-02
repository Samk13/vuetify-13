<template>
  <div class="home">
    <h1>Home page</h1>
    <v-btn depressed rounded class="pink white--text">
      <v-icon left>{{ svgPath }}</v-icon>
      <span>email me</span>
    </v-btn>
    <v-btn depressed small rounded class="pink white--text">
      <v-icon small left>{{ svgPath }}</v-icon>
      <span>email me</span>
    </v-btn>
    <v-btn depressed large rounded class="pink white--text">
      <v-icon large left>{{ svgPath }}</v-icon>
      <span>email me</span>
    </v-btn>
    <v-btn fab depressed small color="purple">
      <v-icon color="white">{{ fav }}</v-icon>
    </v-btn>
  </div>
</template>

<script>
// @ is an alias to /src
import { mdiEmail } from "@mdi/js";
import { mdiHeart } from "@mdi/js";

export default {
  name: "Home",
  data: () => ({
    svgPath: mdiEmail,
    fav: mdiHeart
  })
};
</script>
