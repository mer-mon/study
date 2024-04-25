<script setup>
import { ref } from 'vue';
import S from './S.vue';
let model = ref(0);
</script>
<template>
    <span>F.vue</span>
    <span> value: {{ model }}</span>
    <button @click="model--">F.button</button>
    <S v-model="model" />
</template>