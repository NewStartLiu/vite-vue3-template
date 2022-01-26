<!--
 * @Descripttion:
 * @version:
 * @Author: 刘熠
 * @Date: 2022-01-25 14:57:28
 * @LastEditors: Please set LastEditors
 * @LastEditTime: 2022-01-26 14:02:55
-->
<template>
  <el-button @click="test({ data: 123 })">Default</el-button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { test } from '@/api/index'

export default defineComponent({
  setup() {},
  methods: {
    test(params: Object) {
      test(params)
    }
  }
})
</script>
