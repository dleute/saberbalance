<template>
  <v-layout class="rounded rounded-md border">
    <v-app-bar title="Application bar"></v-app-bar>

    <v-navigation-drawer>
      <v-list nav>
        <v-list-item title="Navigation drawer" link></v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-main class="d-flex align-center justify-center" height="300">
      <v-container>
        <v-row>
            <v-col cols="12"><slot></slot></v-col>
            <v-col cols="12">
        <v-sheet
          border="dashed md"
          color="surface-light"
          rounded="lg"
          width="100%"
        >
        
        <saber-list></saber-list>
        </v-sheet>
        </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-layout>
    
</template>
  
<script setup>
import HelloWorld from './hello.vue'
import SaberList from './saberlist.vue'
</script>
  
<style scoped>

</style>