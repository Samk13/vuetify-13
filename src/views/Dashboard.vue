<template>
  <div class="Dashboard">
    <h1 class="subheading ma-5">Dashboard</h1>
    <v-container class="my-5">
      <v-layout row wrap>
        <v-col v-for="n in 10" :key="n" xs="4" md="2" lg="12">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          <v-btn outlined block class="primary mb-2">
            click me
          </v-btn>
        </v-col>
      </v-layout>
      <v-layout row wrap justify-space-around>
        <v-col v-for="n in 2" :key="n" xs="4" md="3">
          <v-btn outlined block class="primary mb-2">
            click me
          </v-btn>
        </v-col>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Dashboard"
};
</script>
