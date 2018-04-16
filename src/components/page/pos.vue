<template>
  <div id="pos">
    <left-nav>

    </left-nav>
    <el-row >
            <el-col :span='7'>
            我是订单栏
            </el-col>
            <!--商品展示-->
            <el-col :span="17">
             我是产品栏
            </el-col>
    </el-row>
 </div>
</template>

<script>
import LeftNav from './../common/leftNav.vue'
export default {
  name: 'pos',
  data () {
    return {
      msg: 'a'
    }
  },
  components: {
    LeftNav
  }
}
</script>
<style lang='scss' scoped>

</style>
