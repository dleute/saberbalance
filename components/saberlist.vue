<template>
    <v-container fluid>
        <v-row v-for="n in 15" :key="n">
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