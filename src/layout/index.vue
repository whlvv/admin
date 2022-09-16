<template>
  <div h-full bg-gray>
    <el-button type="primary"
      ><div dark:i-ep-moon i-ep-sunny text-lg @click="toggleDark()"></div>
    </el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </div>
</template>
<script setup lang="ts"></script>
<style scoped lang="scss"></style>
