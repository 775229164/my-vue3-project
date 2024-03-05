<script setup>
const btnClick = () => {
  uni.navigateBack();
};
</script>

<template>
  <button @click="btnClick">返回</button>
</template>

<style lang="scss">
</style>