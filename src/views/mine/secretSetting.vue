<template>
  <div class="mine_resume_container">
    <m-header :borderShow="true">
      <div slot="middle" class="center_container">
        隐私设置
      </div>
      <div slot="right">
        <img src="../../assets/img/mine/info.png" style="width: .6rem">
      </div>
    </m-header>

  </div>
</template>

<script>
  import mHeader from '../../components/mHeader'

  export default {
    name: "secretSetting",
    components: {
      mHeader
    }
  }
</script>

<style scoped lang="scss">
  @import "../../style/mixin";

  .mine_resume_container {
    width: 100%;
    height: 100%;
    .center_container {
      width: 80%;
      font-size: 0.4rem;
      font-weight: bold;
    }
  }
</style>
