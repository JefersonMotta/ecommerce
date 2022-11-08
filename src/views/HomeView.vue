<template>
 <v-app>
  <NavBar class="index"/>
  <DashboardComp />
  <FooterComp />
 </v-app>
</template>

<script>
import DashboardComp from '@/components/DashboardComp.vue';
import FooterComp from '@/components/FooterComp.vue';
import NavBar from '@/components/NavBar.vue';


  export default {
    name: 'HomeView',

    components: {
    NavBar,
    DashboardComp,
    FooterComp
},
  
        NavBar}
</script>

<style scoped>
.index{
  z-index: 9999;
}
</style>