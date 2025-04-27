<template>
  <div>
    <h1>欢迎来到首页</h1>
<<<<<<< HEAD
    <AppAlert> 这是一个自动导入的组件44 </AppAlert>
=======
    <AppAlert> 这是一个自动导入的组件22 </AppAlert>
>>>>>>> parent of c281474 (提交)
  </div>
</template>

<script setup>
const description = ref("这是首页");
const keywords = ref("首页,vue3,vite");
useSeoMeta({
  keywords,
  description,
});
</script>
