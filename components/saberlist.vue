<template>
    <v-container fluid>
        <v-row v-for="n in 3" :key="n">
            <v-col cols="12">
                <v-chip-group>
                    <v-chip>Chip 1</v-chip>
                    <v-chip>Chip 2</v-chip>
                    <v-chip>Chip 3</v-chip>
                </v-chip-group>
            </v-col>
            <v-col cols="12">
                <saber></saber>
            </v-col>
        </v-row>
    </v-container>
</template>

<script setup>
import Saber from './saber.vue'
</script>

<style scoped>
</style>