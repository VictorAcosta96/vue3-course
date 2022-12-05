<template>
    <p v-bind:style="{'backgroundColor': background, 'color': colorText}">Texto de prueba</p>
    <button v-on:click="handleClick">Dark mode</button>
</template>

<script setup>
import { ref } from 'vue';

let colorText = ref('#fff')
let background = ref('#000')

const handleClick = ()=>{
    colorText.value = '#000',
    background.value = '#fff'
}
</script>

<style lang="scss" scoped>

</style>