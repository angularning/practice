<template>
  <div class="hello">
    <div>空空如也</div>
    <button>首位</button>
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
  mouted() {
    console.log(12);
    console.log(document.cookie);
  },
  setup() {
    const re = () => {
      console.log(document.cookie);
    };
    const num1 = ref("didi");
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
