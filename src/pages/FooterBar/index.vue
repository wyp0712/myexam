<template>
  <div class="footer-bar">
    <div>
      <router-link to="/">Home</router-link>
    </div>
    <div>
      <router-link to="/admin">admin</router-link>
    </div>
    <div>
      <router-link to="/admin">admin</router-link>
    </div>
  </div>
</template>
<script>
export default {
  name: 'FooterBar',
  data() {
    return {
      msg: 'msg'
    };
  },
  created() {}
};
</script>
<style lang="scss">
%juzhong {
  display: flex;
  justify-content: center;
  align-items: center;
}

.footer-bar {
  width: 100%;
  height: 45px;
  display: flex;
  div {
    flex: 1;
    @extend %juzhong;
  }
}
</style>
