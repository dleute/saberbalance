<template>
  <v-card title="Saber" hover variant="elevated">
    <v-card-text>
      <v-chip-group>
        <v-chip>Chip 1</v-chip>
        <v-chip>Chip 2</v-chip>
        <v-chip>Chip 3</v-chip>
      </v-chip-group>
      <saber-svg></saber-svg>
    </v-card-text>
    <v-card-actions>
      <v-spacer></v-spacer>
      <v-btn rounded="lg" variant="elevated">Edit</v-btn>
    </v-card-actions>
  </v-card>
</template>

<script setup>
import SaberSvg from './svg.vue'
</script>

<style scoped>
</style>