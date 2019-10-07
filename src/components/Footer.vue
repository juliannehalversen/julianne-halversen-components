<template>
<!--
<div class="footerStyles">
  <v-row class="footerStyles">
  <v-card class="footerStyles">
    <v-footer
      fixed = "true"
      class="font-weight-medium footer footerStyles"
    >
    
      <v-col
        class="text-center footerStyles"
        cols="12"
      >
      <strong class="subheading">All servers managed here!</strong>
      </v-col>
    </v-footer>
  </v-card>
  </v-row>
</div>
-->

<div>
  
<v-footer
      dark
      padless
    >
      <v-card
        class="flex"
        flat
        tile
      >
        <v-card-title>
          <strong class="heading">All servers managed here!</strong>
  
          <div class="flex-grow-1"></div>
  
          
        </v-card-title>
  
        <v-card-actions class="grey darken-3 justify-center">
          <strong class="subheading">Julianne Halversen</strong>
        </v-card-actions>
      </v-card>
    </v-footer>
</div>
    
</template>

<script>
export default {
  
}
</script>

<style>
.footerStyles {
  background-color: #424242;
}
.heading {
  color: #f1c031;
  margin-left: 7%;
}
.subheading {
  color: white;
  margin-left: 7%;
}

</style>

