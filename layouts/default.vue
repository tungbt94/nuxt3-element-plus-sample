<template>
  <el-container>
    <el-header>
      Header
    </el-header>
    <el-main>
      Main
      <slot></slot>
    </el-main>
    <el-footer>
      Footer
    </el-footer>
  </el-container>
</template>

<script lang="ts" setup>
import { ElContainer, ElHeader, ElMain, ElFooter } from 'element-plus/dist/index.full.js'
</script>
