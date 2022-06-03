<script setup lang="ts">
import { notification } from 'ant-design-vue'

notification.open({
  message: 'test',
  description: 'description',
  duration: 10000,
})
</script>

<template>
  Test
</template>
