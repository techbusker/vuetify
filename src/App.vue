<template>
  <v-app>
    <v-toolbar absolute dark class="transparent elevation-0">
      <v-toolbar-side-icon class="hidden-md-and-up"></v-toolbar-side-icon>
      <v-toolbar-title>Still Alive Cafe</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
          <v-btn color="" flat>About</v-btn>
          <v-btn color="" flat>Free Delivery</v-btn>
          <v-btn color="" flat>Process</v-btn>
          <v-btn color="" flat>Contact</v-btn>
          <v-btn color="" flat>Sign Up</v-btn>
      </v-toolbar-items>
    </v-toolbar>

    <app-header></app-header>
  </v-app>
</template>

<script>
import Header from './components/Header.vue'

  export default {
    data () {
      return {
       
      }
    },
    components: {
      'app-header': Header
    }
  }
</script>

<style lang="scss">
@import url('https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.0/normalize.css');

</style>
