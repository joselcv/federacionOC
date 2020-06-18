
<!-- Desarrollado por: José luis casanova -->
<template>
  <v-layout> 
<!--  -->
<v-btn icon x-large style="margin-top:4px; margin-right:50px; margin-left:20px;">
    <v-app-bar-nav-icon @click.stop="drawer = !drawer" color="black"></v-app-bar-nav-icon>
</v-btn>
<v-flex xs1 style="margin-left:5px; margin-right:20px; padding-top:20px">
      <img  src="../../public/img/Desktop1904/nammu.io@2x.png" height="20" width="80" />
     </v-flex>
    <v-navigation-drawer
      v-model="drawer"
      fixed
      temporary
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-title>{{ labels.products }}</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>{{ labels.education }}</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>{{ labels.events }}</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>{{ labels.contacts }}</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>

<!-- ///////////////////////////////////////////////////////// -->
        </v-layout>
</template>

<script>
import {labels} from '@/lang/lang';
export default {
  data:() =>({
    labels:labels,
    drawer: false,
      group: null,
  }),
  watch: {
      group () {
        this.drawer = false
      },
    },
}
</script>
<style scoped>
  #toolbar{
    margin-top:20px; 
    margin-bottom:25px; 
    margin-right:20px !important;
  }
  .btnToolbar{
    font-size:18px !important;
    text-transform: capitalize !important;
    font-family: 'Roboto' !important;
    font-weight: 600;
  }
</style>