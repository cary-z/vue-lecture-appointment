<style lang="less" src="./home.less" scoped></style>
<template>
  <div class="home">
    <div class="content">
      <div class="user">
        <div class="left">
          <div class="img"></div>
          <div>
            <div>***</div>
            <div class="font-bold">用户昵称</div>
          </div>
        </div>
        <div class="right">
          <div>
            <div class="font-bold">**</div>
            <div class="font-gray small">积分</div>
          </div>
          <!-- <div>
            <div class="font-bold">**</div>
            <div class="font-gray small">余额</div>
          </div>
          <div>
            <div class="font-bold">0</div>
            <div class="font-gray small">优惠劵</div>
          </div> -->
        </div>
      </div>
      <div class="box">
        <div class="box-item">
          <img src="/static/images/info.svg" alt="">
          <div>讲座信息</div>
        </div>
        <div class="box-item">
          <img src="/static/images/book.svg" alt="">
          <div>预约入口</div>
        </div>
        <div class="box-item">
          <img src="/static/images/feedback.svg" alt="">
          <div>反馈交流</div>
        </div>
      </div>
      <!-- <div class="gray content-item"></div>
      <div class="gray content-item"></div>
      <div class="gray content-item"></div>
      <div class="gray content-item"></div> -->
      <div class="content-item" v-for="index in 6">
        <img width="100%" height="100%" :src="`/static/images/school${index}.jpg`" alt="">
      </div>
      <div></div>
    </div>
    <!-- 底部的固定导航栏 -->
    <Footer-nav></Footer-nav>
  </div>
</template>

<script>
import FooterNav from '../common/footerNav/footer_nav'
export default {
  name: 'home',
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
