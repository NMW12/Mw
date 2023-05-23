<template>
  <v-app>
     <v-content>  
      <Nav></Nav>
    <router-view></router-view>
   </v-content>
  </v-app>
</template>

<script>
import Nav from '@/components/Navbar.vue'
export default {
  name: 'App',

  data: () => ({
    Nav
  }),
};
</script>
