<template>
  <div>
    <v-app-bar
      app
      absolute
      color="black lighten-1"
      dark
      :collapse-on-scroll="collapseOnScroll"
      scroll-target="#scrolling-techniques-6"
    >
      <div class="d-flex align-center">

        <h1>Found</h1>

      </div>

      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn outlined raised text> Data </v-btn>
        <v-btn outlined raised text> Sign In </v-btn>
      </v-toolbar-items>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style lang="">
</style>