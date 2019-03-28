<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Dperry</span>
        <span class="font-weight-light">.io</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        to="/"
        target="_blank"
        class="navbar-page-names"
      >
      Home
      </v-btn>

      <v-btn
        flat
        to="/about"
        class="navbar-page-names"
      >
      About
      </v-btn>

      <v-btn
        flat
        to="/blog"
        class="navbar-page-names"
      >
      Blog
      </v-btn>
      

      <!-- <v-btn
        flat
        href="https://github.com/dfperry5"
        target="_blank"
        class="navbar-social-icon"
      >
        <v-icon>mdi-file-pdf</v-icon>
      </v-btn>

      <v-btn
        flat
        href="https://github.com/dfperry5"
        target="_blank"
        class="navbar-social-icon"
      >
        <v-icon>mdi-github-circle</v-icon>
      </v-btn>

      <v-btn
        flat
        href="https://github.com/dfperry5"
        target="_blank"
        class="navbar-social-icon"
      >
        <v-icon>mdi-linkedin</v-icon>
      </v-btn> -->
    </v-toolbar>

    <v-content>
      <router-view></router-view>    
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>

<style>
.navbar-page-names{
  margin: 0;
}
</style>
