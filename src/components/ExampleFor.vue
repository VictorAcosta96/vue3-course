<template>
    <ul>
        <li v-for="team in footballTeams" :key="team.id">{{team.name}} - {{team.country}}</li>
    </ul>
</template>

<script setup>
import { ref } from 'vue';

let footballTeams = ref([
    {
        id:1,
        name: "Manchester united",
        country: "England"
    },
    {
        id:2,
        name: "Barcelona",
        country: "Spain"
    },
    {
        id:3,
        name: "Milan",
        country: "Italy"
    },
    {
        id:4,
        name: "Bayern munich",
        country: "Germany"
    }
])
</script>