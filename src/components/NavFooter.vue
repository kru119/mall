<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt="">
      <p>小米商城</p>
    </div>
    <div class="footer-link">
      <a href="javascript:;">帮助中心</a>
      <a href="javascript:;">联系我们</a>
      <a href="javascript:;">服务支持</a>
      <a href="javascript:;">线下门店</a>
    </div>
    <div class="copyright">Copyright ©2020 <span class="domain">mi.futurefe.com</span>All Rights Reserved.</div>
  </div>
</template>

<script>
export default {
  name:'nav-footer'
}
</script>

<style lang="scss" scoped>
  .footer{
    // position: absolute;
    // bottom: 0px;
    width: 100%;
    height: 180px;
    border-top: 2px solid #FF6600;
    background-color: #333333;
    color: #999999;
    font-size: 16px;
    text-align: center;
    .footer-logo{
      margin-top: 46px;
      margin-bottom: 31px;
      img{
        width: 53px;
        height: 36px;
      }
    }
    .footer-link{
      a{
        color: #999999;
        display: inline-block;
        padding-right: 10px;
      }
      span{
        margin: 0 10px;
      }
    }
    .copyright{
      .domain{
        color:#FF6600;
      }
    }
  }

</style>