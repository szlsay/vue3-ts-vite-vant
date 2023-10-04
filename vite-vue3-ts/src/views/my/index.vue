<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
  .col-9{
    color: #999999;
  }
  >>>.van-nav-bar{
    background: none;
  }
  >>>.van-nav-bar__title{
    color: #ffffff;
    font-size:0.96rem;
  }
  >>>.van-nav-bar .van-icon{
    font-size: 1.12rem;
    color: #ffffff;
  }
  >>>.van-hairline--bottom:after{
    border:0;
  }
  >>>.van-nav-bar__right{
    padding-right: 0;
  }
  .my-page{
    padding: 0 0.77rem 3rem;
    background: #FBFBFB url(@/assets/img/my/top-background.png) center -0.8rem no-repeat;
    background-size: contain;
    height: calc(100vh - 3rem);
    overflow: auto;
  }
  .my-info{
    display: flex;
    align-items: center;
    margin: 0.8rem 0 0.93rem;
    position: relative;
    right: -0.77rem;
  }
  .my-info img{
    width: 3.2rem;
    height: 3.2rem;
    border-radius: 50%;
    margin-right: 0.85rem;
  }
  .my-info div h3{
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-weight: 400;
    color: #FFFFFF;
    margin-bottom: 0.48rem;
  }
  .my-info div h3 span{
    width: 0.56rem;
    height: 0.56rem;
    margin-left: 0.59rem;
    display: inline-block;
    background: url(@/assets/img/my/icon-edit.png) no-repeat;
    background-size: 100%;
  }
  .my-info div p{
    font-size: 0.69rem;
    line-height: 0.69rem;
    font-weight: 400;
    color: #FFFFFF;
  }
  .my-info i{
    width: 4.91rem;
    height: 1.49rem;
    background: url(@/assets/img/my/icon-my-account.png) no-repeat;
    background-size: 100%;
    position: absolute;
    right: 0;
  }
  .my-type{
    display: flex;
    align-items: center;
    height: 3.31rem;
    background: #FFFFFF;
    box-shadow: 0rem 0rem 1rem 0rem rgba(49,57,73,0.09);
    border-radius: 0.27rem;
    margin-bottom: 0.53rem;
  }
  .my-type strong{
    width: 0.03rem;
    height: 1.95rem;
    background: #EDEDED;
    margin-left: 1.92rem;
  }
  .my-type a{
    display: flex;
    align-items: center;
    margin-left: 1.92rem;
  }
  .my-type a img{
    width: 2.24rem;
    height: 2.24rem;
    margin-right: 0.51rem;
  }
  .my-type a span{
    font-size: 0.69rem;
    line-height: 0.69rem;
    font-weight: 400;
    color: #666666;
  }
  .my-type-enterprise{
    display: flex;
    width: 18.45rem;
    height: 5.27rem;
    border-radius: 0.27rem;
    background: #ffffff;
    margin-bottom: 0.59rem;
  }
  .my-type-enterprise a{
    display: flex;
    flex-direction: column;
    flex: 1;
    align-items: center;
    justify-content: center;
    position: relative;
  }
  .my-type-enterprise a img{
    width: 2.45rem;
    height: 2.45rem;
    margin-bottom: 0.64rem;
  }
  .my-type-enterprise a span{
    font-size: 0.64rem;
    color: #333333;
  }
  .my-type-enterprise a i{
    position: absolute;
    font-style: normal;
    font-size: 0.59rem;
    color: #FFFFFF;
    width: 0.85rem;
    height: 0.85rem;
    background: #FC9215;
    border: 1px solid #FFFFFF;
    border-radius: 50%;
    text-align: center;
    left: 50%;
    margin-left: 0.4rem;
    top: 0.6rem;
  }
  .my-contract{
    height: 7.9rem;
    background: #FFFFFF;
    border-radius: 0.27rem;
    margin-bottom: 0.59rem;
  }
  .my-title{
    height: 2.69rem;
    border-bottom: 1px solid #eeeeee;
    display: flex;
    align-items: center;
    padding: 0 0.8rem;
  }
  .my-title h3{
    font-size: 0.8rem;
    line-height: 0.8rem;
    font-weight: 400;
    color: #333333;
    flex: 1;
  }
  .my-title span{
    text-align: right;
    font-size: 0.64rem;
    color: #464646;
  }
  .my-contract-cur{
    height: 5.17rem;
    display: flex;
    align-items: center;
    vertical-align: center;
  }
  .my-contract-cur span{
    flex: 1;
    text-align: center;
    font-size: 0.69rem;
    color: #464646;
  }
  .my-contract-cur span img{
    width: 1.39rem;
    height: 1.39rem;
    display: block;
    margin: 0 auto 0.59rem;
  }
  .my-common{
    background: #FFFFFF;
    border-radius: 0.27rem;
    margin-bottom: 0.59rem;
  }
  .my-item{
    height: 2.67rem;
    background: #FFFFFF;
    border-bottom: 1px solid #eeeeee;
    display: flex;
    align-items: center;
    padding: 0 0.4rem 0 0rem;
    margin-left: 0.69rem;
    font-size: 0.69rem;
    color: #464646;
  }
  .my-item:last-child{
    border-bottom: 0;
  }
  .my-item img{
    width: 1.12rem;
    height: 1.12rem;
    margin-right: 0.85rem;
  }
  .my-item label{
    flex: 1;
  }
  .my-item span{
    display: flex;
    align-items: center;
    text-align: right;
  }
  .my-item span img{
    width: 1.28rem;
    height: 1.28rem;
    border-radius: 50%;
    margin-right: 0.32rem;
  }
</style>