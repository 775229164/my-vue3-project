<script setup>
import { ref } from "vue";

const name = ref("");

const nextClick = () => {
  uni.navigateTo({ url: "/pages/next/next" });
};
</script>

<template>
  <input v-model="name" placeholder="请输入姓名" />

  <button @click="nextClick">下一页</button>
</template>

<style lang="scss">
</style>
