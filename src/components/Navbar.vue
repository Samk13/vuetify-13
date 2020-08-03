<template>
  <nav>
    <v-toolbar app flat>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Todo</span>
        <span>Sam</span>
      </v-toolbar-title>
      <v-spacer />
      <v-btn flat color="grey">
        <span>Sign Out</span>
        <v-icon right>{{ signOut }}</v-icon>
      </v-btn>
    </v-toolbar>
  </nav>
</template>

<script>
import { mdiExitToApp } from "@mdi/js";
export default {
  data: () => ({
    signOut: mdiExitToApp
  })
};
</script>
