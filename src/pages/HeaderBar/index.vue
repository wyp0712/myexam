<template>
  <div class="header-bar">
    <div class="header-bar-left"></div>
    <div class="header-bar-mid">测试系统</div>
    <div class="header-bar-right"></div>
  </div>
</template>
<script>
export default {
  name: 'HeaderBar',
  data() {
    return {
      msg: 'test'
    };
  },
  created() {},
  mounted() {}
};
</script>
<style lang="scss">
.header-bar {
  width: 100%;
  height: 45px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: orangered;
  .header-bar-left {
    flex: 1;
  }
  .header-bar-mid {
    flex: 8;
  }
  .header-bar-right {
    flex: 1;
  }
}
</style>
