<style lang="less" src="./profile.less" scoped></style>
<template>
  <div class="profile">
    <div class="green"></div>

    <div class="content">
      <div class="content-item user-info">
        <div class="user-img"></div>
        <div></div>
      </div>
      <div class="content-item service">
        <div class="title">我的服务</div>
        <div class="icons">
          <div class="icon-item">
            <img class="icon" src="/static/images/history.svg" alt="">
            <div class="text">讲座记录</div>
          </div>
          <div class="icon-item">
            <img src="/static/images/help.svg" alt="">
            <div class="text">帮助中心</div>
          </div>
          <!-- <div class="icon-item">领券中心</div>
          <div class="icon-item">领券中心</div>
          <div class="icon-item">领券中心</div>
          <div class="icon-item">领券中心</div>
          <div class="icon-item">领券中心</div> -->
        </div>
      </div>
    </div>

    <!-- 底部的固定导航栏 -->
    <Footer-nav></Footer-nav>
  </div>
</template>

<script>
import FooterNav from '../common/footerNav/footer_nav'
export default {
  name: 'discover',
  data () {
    return {
    }
  },
  mounted () {
  },
  computed: {
  },
  methods: {

  },
  components: {
    FooterNav
  }
}
</script>
