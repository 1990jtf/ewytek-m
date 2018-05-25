<template>
  <div id="contact">
    <nav-bar></nav-bar>
    <banner></banner>
    <div class="contact-content m-wrapper">
      <p>市场合作: ewytek@163.com</p>
      <br/>
      <p>媒体联系: ewytek@163.com</p>
      <br/>
      <p>CEO邮箱: 15043153@qq.com</p>
      <br/>
      <p>联系电话: 136-7337-2775</p>
      <br/>
      <p>地址: 郑州市中原区升龙金中环B座1306室</p>
    </div>
    <foot></foot>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar'
import Foot from '@/components/Foot'
import Banner from '@/components/Banner'
export default {
  name: 'Contact',
  components: {
    NavBar,
    Foot,
    Banner
  }
}
</script>
<style lang="stylus" scoped>
.contact-content
  margin 40px 0
  p
    font-size 28px
    line-height 40px
    color #707473
</style>
