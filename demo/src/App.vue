<template>
  <div id="app">
    <el-radio-button  label="1">备选项</el-radio-button>
  </div>
</template>

<script>
// 单个引入, 在 node_modules/element-ui/packages/ 打断点
import ElRadioButton from "element-ui/packages/radio/src/radio-button.vue";

export default {
  name: "App",
  components: {
   ElRadioButton,
  }
};
</script>

<style>
</style>
