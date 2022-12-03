<template>
    <h3>{{counter}}</h3>
    <button @click="addCounter">Incremente</button>
</template>


<!-- setup en el script -->
<script setup>
import {ref} from 'vue'
        let counter = ref(0)
        const addCounter = () => {
            counter.value++            
        }
</script>


<!-- <script>
import { defineComponent,ref } from 'vue';
export default defineComponent({
    name: "CounterComposition",
    setup(){
        let counter = ref(0)
        const addCounter = () => {
            counter.value++            
        }
        return {counter, addCounter}
    }
})
</script> -->




<style scoped>

</style>