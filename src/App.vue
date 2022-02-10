<template>
  <v-app>
    <Navigation />
    <v-main>
      Hello world
      <div id="map" class="map">
        <Map />
      </div>
    </v-main>
  </v-app>
</template>

<script>
import Map from './components/Map.vue';
import Navigation from './components/Navigation.vue';

export default {
  name: 'App',

  components: {
    Map,
    Navigation,
  },

  data: () => ({
    //
  }),
};
</script>

<style lang="scss">

  .map {
    display: flex;
    position: center;
    margin: auto;
    width: 90%;
    height: 50%;
    border-radius: 25px;
}
</style>
