<!--  -->
<script setup>
import MyButton from './components/MyButton.vue';

</script>
<template>
    <!-- Here we pass class attribute as prop: attribute inheritance -->
    <MyButton class="fancy-btn"></MyButton>
</template>
<style>
.fancy-btn {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline;
    font-size: 16px;
}
</style>