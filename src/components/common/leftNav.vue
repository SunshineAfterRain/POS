<template>
  <div class="left-nav">
    <ul>
      <li>
        <i class="icon iconfont icon-wodezichan"></i>
        <div>收银</div>
      </li>
      <li>
        <i class="icon iconfont icon-dianpu"></i>
        <div>店铺</div>
      </li>
      <li>
        <i class="icon iconfont icon-hanbao"></i>
        <div>商品</div>
      </li>
      <li>
        <i class="icon iconfont icon-huiyuanqia"></i>
        <div>会员</div>
      </li>
      <li>
        <i class="icon iconfont icon-tongji"></i>
        <div>统计</div>
      </li>
    </ul>
  </div>
</template>
<script>
  export default {
    name: 'leftNav',
    data () {
      return {
        msg: 'aaa'
      }
    }
  }
</script>
<style lang="scss" scoped>
    .left-nav {
        ul {
            width: 80px;
            height: 100%;
            color: #ffffff;
            li {
                width: 100%;
                padding: 10px 0 ;
                text-align: center;
                background-color: blue;
            }
        }
    }
</style>
