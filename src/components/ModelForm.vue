<template>
    <form>
        <input type="text" v-model="inputText">
        <input type="checkbox" v-model="agree">
        <select v-model="teams">
            <option value="ManUtd">Manchester United</option>
            <option value="Barca">Barcelona</option>
            <option value="Milan">Milan</option>
        </select>
    </form>

    <h3>{{inputText}}</h3>
</template>

<script>
 import {defineComponent } from 'vue';
export default defineComponent({
    name:"ModelForm",
    data(){
        return {inputText:"",agree:true,teams:"ManUtd"}
    }
})
</script>

<style scoped>

</style>