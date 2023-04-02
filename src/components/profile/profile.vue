<style lang="less" src="./profile.less" scoped></style>
<template>
  <div class="profile">
    <div class="green"></div>

    <div class="content">
      <div class="content-item user-info">
        <div class="user-img"></div>
        <div></div>
      </div>
      <div class="content-item">我的服务</div>
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
