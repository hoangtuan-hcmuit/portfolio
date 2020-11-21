<template>
  <v-app>
    <Navigation />
    <router-view></router-view>
    <Footer />
  </v-app>
</template>

<script>
import Navigation from './components/nav';
import Footer from './components/footer'

export default {
  name: 'App',

  components: {
    Navigation, Footer,
  },

  data: () => ({
    //
  }),
};
</script>
