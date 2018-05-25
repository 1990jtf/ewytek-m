<template>
  <div id="company">
    <nav-bar></nav-bar>
    <banner></banner>
    <div class="company-content m-wrapper">
      <p>河南省易维泰克科技有限公司，是由专业技术人员发起并创办的一家民营企业。</p>
      <br/>
      <p>在长期服务市场开拓和创业实践中，步积累了工程造价咨询、股票投资理财、共享经济、政务党务督查、供应链金融、公安指挥调度、情报分析等方面的业务基础。</p>
      <br/>
      <p>成长起来一批支撑易维泰克事业稳步发展的梯队力量，涌现一批能够“勇挑创业重任、坚持挑战更高标准、努力学习一专多能、不断提高综合业务素质”的青年人最终形成了一支 由软件专业技术为主体、富有蓬勃向上的创新型集体创业团队，易维泰克人正迎着国家信息化发展的东风，昂首前进。
      </p>
    </div>
    <foot></foot>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'
import Foot from '@/components/Foot'
import Banner from '@/components/Banner'
export default {
  name: 'Company',
  components: {
    NavBar,
    Foot,
    Banner
  }
}
</script>
<style lang="stylus" scoped>
.company-content
  margin 40px 0
  p
    font-size 28px
    line-height 40px
    color #707473
    text-indent 2em
</style>
