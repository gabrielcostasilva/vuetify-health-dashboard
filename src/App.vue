<template>
  <v-app>
    <side-bar />

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import SideBar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    SideBar
  },
  data: () => ({
    //
  }),
};
</script>
