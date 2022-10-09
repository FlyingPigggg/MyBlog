<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      个人博客后台管理系统
    </div>
    <br />
    <div>
      有问题欢迎联系我的QQ：1036634677
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
