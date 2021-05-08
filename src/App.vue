<template>
  <v-app>
    <v-main>
      <Reserva/>
    </v-main>
  </v-app>
</template>

<script>
import Reserva from './components/reserva.vue';
module.exports = {
  entry:'./components/timeline/timeline.html'
}

export default {
  name: 'App',

  components: {
    Reserva,
  },

  data: () => ({
    //
  }),
};
</script>
