<script setup>
import { ref } from 'vue'
let counter = ref(0)
</script>
<template>
    <div>
        <h1>Counter {{ counter }}</h1>
        <button @click="counter++">+</button>
    </div>
</template>