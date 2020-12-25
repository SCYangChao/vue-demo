<template>
  <div>
    <!-- 使用子组件,使用-，不建议使用驼峰 -->
    <RightLayout></RightLayout>
    <LeftLayout></LeftLayout>
  </div>
</template>
<script>
  // 会导入./AppHeader下面的index.vue组件
  import RightLayout from "./RightLayout"
  import LeftLayout from "./LeftLayout"
  export default {
    components: { RightLayout, LeftLayout }
  };
</script>
<style>

</style>
