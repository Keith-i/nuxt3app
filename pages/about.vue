<template>
  <div>关于我们</div>
</template>

<script setup>
const description = ref("这是关于我们页");
const keywords = ref("关于我们,vue3,vite");
useSeoMeta({
  keywords,
  description,
});
</script>
