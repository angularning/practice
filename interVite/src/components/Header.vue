<template>
  <div class="header">
    <marquee>哈哈哈您已升级为借钱特权用户，邀您走绿色申请通道，名额有限先到先得</marquee>
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
  padding: 30px;
  
}
a {
  color: #42b983;
}
</style>
