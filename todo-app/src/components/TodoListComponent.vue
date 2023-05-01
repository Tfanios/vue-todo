<script setup>

import {ref, onMounted, computed, watch} from 'vue'

const todos = ref([])
const name = ref('')

onMounted(()=>{
  name.value = localStorage.getItem('name') || ''
})


</script>

<template>
    <h1>List of todos</h1>
</template>

<style scoped>

</style>