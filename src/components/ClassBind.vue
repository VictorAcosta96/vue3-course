<template>
    <p v-bind:class="{'danger': hasError}">El mensaje se ha enviado correctamente</p>

    <!-- abreviacion del v-bind -> : -->
    <!-- <p :class="{'danger': hasError}">El mensaje se ha enviado correctamente</p> -->
</template>

<!-- composition api setup en el script -->
<script setup>
let hasError = true
</script>

<!-- composition api standar -->
<!-- <script>
   import { defineComponent } from 'vue';
   export default defineComponent({
    name: 'ClassBind',
    setup(){
        return{
            hasError: true
        }
    }
   })
</script> -->

<!-- option api -->
<!-- <script>
 import { defineComponent } from 'vue';
   export default defineComponent({
    name: 'ClassBind',
    data(){
        return{
            hasError: true
        }
    }
   })
</script> -->

<style scoped>
.danger{
    color: red;
}
</style>