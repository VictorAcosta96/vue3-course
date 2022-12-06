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
 import {defineComponent,ref } from 'vue';
export default defineComponent({
    name:"ModelForm",
    setup(){
        let inputText = ref('')
        let agree = ref(true)
        let teams = ref('Milan')
        return {inputText,agree,teams}
    }
})
</script>

<style scoped>

</style>