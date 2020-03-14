<template>
  <div id="app">
    <el-row>
      <el-col :span="12">
        <div class="grid-content bg-purple-dark">a</div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import 'element-ui/lib/theme-chalk/index.css';
// 单个引入, 在 node_modules/element-ui/packages/ 打断点
import ElRadioButton from "element-ui/packages/radio/src/radio-button.vue";
import ElRow from "element-ui/packages/row/index";
import ElCol from "element-ui/packages/col/index";

export default {
  name: "App",
  /* eslint-disable vue/no-unused-components */
  components: {
    ElRadioButton,
    ElRow,
    ElCol
  }
};
</script>

<style>
</style>
/* eslint-enable no-alert, no-console */