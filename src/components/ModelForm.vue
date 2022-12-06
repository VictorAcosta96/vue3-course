<template>
    <form>
        <input type="text" v-model="inputText">
    </form>

    <h3>{{inputText}}</h3>
</template>

<script setup>
 import { ref } from 'vue';

 let inputText = ref('')
</script>

<style scoped>

</style>