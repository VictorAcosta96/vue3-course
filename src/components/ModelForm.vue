<template>
    <form>
        <input type="text" v-model="inputText">
    </form>

    <h3>{{inputText}}</h3>
</template>

<script>
 import { ref, defineComponent } from 'vue';
export default defineComponent({
    name:"ModelForm",
    setup(){
        let inputText = ref('')
        return {inputText}
    }
})
</script>

<style scoped>

</style>