<template>
  <v-app>
    <v-app-bar
      app
      color="indigo darken-2"
      dark
    >
      <div class="d-flex align-center">
      </div>

      <v-spacer></v-spacer>

      <v-btn
      to="/"
        text
        style="margin-left: 5px"
      >
        <span class="mr-2">Home</span>
      </v-btn>
         <v-btn
         to="/product"
        text
        style="margin-left: 5px"
      >
        <span class="mr-2">Products</span>
      </v-btn>
         <!-- <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Products</span>
      </v-btn> -->
        <v-text-field
        style="margin-left: 5px"
        flat
        hide-details
        label="Search"
        prepend-inner-icon="mdi-magnify"
        solo-inverted
      ></v-text-field>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  })
}
</script>
