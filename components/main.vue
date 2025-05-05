<template>
    <hello-world></hello-world>
    <h3>And that's it!</h3>
    <saber-list></saber-list>
</template>
  
<script setup>
import HelloWorld from './hello.vue'
import SaberList from './saberlist.vue'

export default {
    name: 'MainApp',
}
</script>
  
<style scoped>
h3 {
    color: white;
    font-size: 1rem;
}
</style>