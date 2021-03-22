<template>
  <div class="hello">
    {{num1}}
    <a @click="toUrl">点击这个</a>
    <!-- <input type="text" v-model="num1" @keyup="add" />
    <span>+</span>
    <input type="text" v-model="num2" @keyup="add" />
    <span>=</span>
    <span>{{ result }}</span> -->
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  setup() {
    const re = ()=>{};
    const num1 = ref('didi');
    const num2 = ref(0);
    const result = ref(0);
    const add = () => {
      result.value = parseInt(num1.value) + parseInt(num2.value);
    };
    return {
      num1,
      num2,
      result,
      add,
      re
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
