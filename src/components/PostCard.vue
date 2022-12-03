<template>
    <div class="post-card">
        <h2>card title</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod totam aut dolore fugiat nemo cum placeat eaque velit voluptate excepturi architecto nobis amet cupiditate, exercitationem, ut sequi maiores quae magni.</p>
        <PostButton/>
    </div>
</template>

<script setup>
import PostButton from './PostButton.vue';
</script>

<style scoped>
.post-card{
    padding: 10px;
    margin: 10px;
    border-radius: 15px;
    border: 1px solid #333;
}
</style>