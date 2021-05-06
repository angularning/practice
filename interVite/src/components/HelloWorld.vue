<template>
  <div>
      <div>this is my web application</div>
      <img class="imgs" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fku.90sjimg.com%2Felement_origin_min_pic%2F16%2F11%2F10%2F125823fd6709123.jpg%21%2Ffwfh%2F804x569%2Fquality%2F90%2Funsharp%2Ftrue%2Fcompress%2Ftrue&refer=http%3A%2F%2Fku.90sjimg.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1622101303&t=f7bd441b8cee4157f1dfa08214d34043" alt="">
      <div>write code , change world !</div>
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
a {
  color: #42b983;
}
.imgs{
  width: 500px;
}
.imgs:hover{
  filter: blur(3px)
}
</style>
