<template>
  <v-parallax src="/saberbalance/assets/img/saber-bg.png">
  <v-layout class="rounded rounded-md border">
  
    <!-- <v-app-bar title="Lightsaber Balance"></v-app-bar> -->

    <!-- <v-navigation-drawer>
      <v-list nav>
        <v-list-item title="Navigation drawer" link></v-list-item>
      </v-list>
    </v-navigation-drawer> -->

    <v-main class="d-flex align-center justify-center">
      <v-container>
        <v-row>
            <v-col cols="12"><slot></slot></v-col>
            </v-row>
            <v-row>
            <v-col cols="12">
        
        <saber-list></saber-list>
        </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-layout>
</v-parallax>
</template>
  
<script setup>
// import HelloWorld from './hello.vue'
import SaberList from './saberlist.vue'
</script>
  
<style scoped>

</style>