<script setup>
import { ref } from 'vue';
import PS from  './PS.vue';
let value = ref('msg');
</script>
<template>
    <span>PF.vue</span>
    <input type="text" v-model="value">
    <PS :greeting-message="value" />
</template>