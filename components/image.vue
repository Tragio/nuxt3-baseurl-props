<template>
  <div>
    <img :src="props.image" />
  </div>
</template>

<script setup>
const props = defineProps({
  image: {
    type: String,
    required: true,
  },
});
</script>
