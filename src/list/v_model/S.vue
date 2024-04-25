<script setup>
import { defineModel } from 'vue';
let model = defineModel();
</script>
<template>
    <div>
        <span>S.vue</span>
        <span> value: {{ model }}</span>
        <button @click="model++">S.button</button>
    </div>
</template>