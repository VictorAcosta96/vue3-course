<template>
    <form>
        <input type="text" v-model="inputText">
    </form>

    <h3>{{inputText}}</h3>
</template>

<script>
 import {defineComponent } from 'vue';
export default defineComponent({
    name:"ModelForm",
    data(){
        return {inputText:""}
    }
})
</script>

<style scoped>

</style>