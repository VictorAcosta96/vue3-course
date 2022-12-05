<template>
    <h2 v-if="age>=18" >Eres mayor de edad</h2>
    <h2 v-else>Eres menor de edad</h2>

    <p v-show="active">activo</p>
</template>

<script setup>
let age = 26;
let active = true
</script>

<style scoped>
</style>