<script setup>
let props = defineProps({
    greetingMessage: String,
});
</script>

<template>
    <div>
        <span>FS.vue </span>
        <span>{{ props.greetingMessage }}</span>
    </div>
</template>