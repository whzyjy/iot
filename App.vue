<template>
  <v-app>
    <Navbar></Navbar>
    <v-contenr>
      <router-view>

      </router-view>
    </v-contenr>
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar';

export default {
    name: "App",
    components : {
      Navbar
    },
    data: () => ({
    //
    }),

};
</script>
