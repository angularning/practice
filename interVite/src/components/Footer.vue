<template>
  <div class="footers">
      <div class="footer"><a href="https://beian.miit.gov.cn">京ICP备18042167号-1</a></div>
  </div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})
const state = reactive({ count: 0 })
</script>

<style scoped>
.footers{
  width:100%;
  position: absolute;
  bottom: 0;
  text-align: center;
  padding: 30px 0;
  
}
a {
  color: #42b983;
}
</style>
