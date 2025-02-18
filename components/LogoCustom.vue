<script setup>
defineProps({
  image: String,
 
});
</script>

<template>
<img :src="image" alt="img">
</template>