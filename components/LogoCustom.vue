<script setup>
defineProps({
    image: String,
    height: String,
    width: String,
});
</script>

<template>
    <img :src="image" alt="img" :height="height" :width="width">
</template>