<script setup lang="ts">
</script>

<template>
  <div class=".box">
    流程测试Test 流程测试Test 流程测试Test
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.box {
  width: 500px;
  height: 500px;
  background-color:aqua;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
  text-align: center;
  font-size: 30px;
  line-height: 500px;
  color: black;
}
</style>
