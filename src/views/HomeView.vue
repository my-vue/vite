<template>
  <main>
    <TheWelcome />
  </main>
</template>

<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import { ref } from 'vue'
const f = ref('asdfasdfasdf')
console.log(f, 'sdfsdaf')
const aa = '张三dddddd'
console.log(aa, 'asdf', 'sadfasdf', 'asdf')
</script>
