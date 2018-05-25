<template>
  <div id="culture">
    <nav-bar></nav-bar>
    <banner></banner>
    <div class="culture-content m-wrapper">
      <p>奉行“诚信、共享” 的企业文化</p>
      <br/>
      <p>奉行“热情、高效”的服务理念</p>
      <br/>
      <p>奉行“求实、创新、极简”的设计理念</p>
    </div>
    <foot></foot>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar'
import Foot from '@/components/Foot'
import Banner from '@/components/Banner'
export default {
  name: 'Culture',
  components: {
    NavBar,
    Foot,
    Banner
  }
}
</script>
<style lang="stylus" scoped>
.culture-content
  margin 40px 0
  p
    font-size 28px
    line-height 40px
    color #707473
</style>
