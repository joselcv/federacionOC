
<!-- Desarrollado por: José luis casanova -->
<template>
  <v-layout>
    <v-tabs  id="toolbar"  color="black" height="50" width="600">
      <v-flex xs1 style="margin-left:2%;padding-top:1%">
      <v-img  src="../../public/img/Desktop1904/nammu.io@2x.png" height="15" width="80" />
     </v-flex>
                        <!-- class="select" -->
              <v-tab class="btnToolbar" style="width:150px; margin-top:10px">
                  <v-select
                  style="border-color:transparent"
                        :items="items"
                        :label="labels.text"
                      ></v-select>
                </v-tab>
                        <v-tab class="btnToolbar">
                {{ labels.text }}
                </v-tab>
                        <v-tab class="btnToolbar">
                {{ labels.text }}
                </v-tab>
                        <v-tab class="btnToolbar">
                {{ labels.text }}
                </v-tab>
                        <v-tab class="btnToolbar">
                {{ labels.text }}
                </v-tab>
                        <v-btn class="btnToolbarEs" color="#C3A059" dark width="150">
                {{ labels.text }}
                </v-btn>
              </v-tabs>
        </v-layout>
</template>

<script>
import {labels} from '@/lang/lang';
export default {
  data:() =>({
    labels:labels,
    items: ['texto 1', 'texto 2', 'texto 3', 'texto 4'],
  })
}
</script>
<style >
  #toolbar{
    padding-top:100px;
    margin-bottom:25px; 
    margin-right:20px !important;
    z-index: 1;
  }
  .btnToolbar{
    font-size:16px !important;
    /* text-transform: capitalize !important; */
    font-family: 'Roboto' !important;
    font-weight: 600;
  }
  .btnToolbarEs{
    margin-top:7px;
    font-size:13px !important;
    /* text-transform: capitalize !important; */
    font-family: 'Roboto' !important;
    font-weight: 500;
    border-radius: 40px;
  }
  .select{
    width: 20%;
    font-size:13px !important;
    text-transform: uppercase !important; 
    font-family: 'Roboto' !important;
    font-weight: 600;
  }
</style>