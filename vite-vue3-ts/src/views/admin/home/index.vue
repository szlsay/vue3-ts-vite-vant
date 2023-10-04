<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
  .van-nav-bar{
    background: #f6f6f6;
  }
  .admin-page{
    padding: 0 0.64rem 4rem;
    background: #f6f6f6;
    min-height: 100vh;
  }
  .admin-banner{
    position: relative;
  }
  .admin-banner img{
    width: 100%;
  }
  .admin-banner p{
    position: absolute;
    top:3.1rem;
    left:1.2rem;
    font-size: 0.69rem;
    font-weight: 300;
    color: #FFFFFF;
  }
  .admin-job{
    overflow: hidden;
  }
  .admin-job a{
    width: 49%;
    height: 4.45rem;
    background: #FFFFFF;
    border-radius: 0.53rem;
    margin-right: 2%;
    margin-bottom: 0.56rem;
    float: left;
    display: flex;
    align-items: center;
  }
  .admin-job a:nth-child(2n){
    margin-right: 0;
  }
  .admin-job a img{
    width: 2.45rem;
    height: 2.45rem;
    margin: 0 0.56rem 0 0.72rem;
  }
  .admin-job a h4{
    font-size: 0.8rem;
    line-height: 0.8rem;
    font-weight: 400;
    color: #333333;
  }
  .admin-job a h4 span{
    font-size: 0.64rem;
    line-height: 0.64rem;
    font-weight: 300;
    color: #333333;
    margin-top: 0.45rem;
    display: block;
  }
  .admin-title{
    display: flex;
    align-items: center;
    margin-bottom: 0.67rem;
    margin-top: 1.44rem;
  }
  .admin-title h3{
    flex: 1;
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-weight: bold;
    color: #333333;
    position: relative;
    margin-bottom: 0.4rem;
  }
  .admin-title h3 i{
    width: 1.87rem;
    height: 0.64rem;
    background: linear-gradient(90deg, #FE8F27,#ffffff);
    opacity: 0.46;
    border-radius: 0.32rem;
    position: absolute;
    left: -0.1rem;
    top: 0.4rem;
    opacity: 0.4;
  }
  .admin-title dl{
    display: flex;
    font-size: 0.59rem;
    line-height: 0.59rem;
    font-weight: 400;
    color: #666666;
  }
  .admin-title dl dt{
    margin-right: 0.77rem;
  }
  .admin-title dl dt::before{
    content: '';
    width: 0.37rem;
    height: 0.37rem;
    background: #6DA6EA;
    border-radius: 50%;
    margin-right: 0.24rem;
    display: inline-block;
  }
  .admin-title dl dd::before{
    content: '';
    width: 0.37rem;
    height: 0.37rem;
    background: #FBC605;
    border-radius: 50%;
    margin-right: 0.24rem;
    display: inline-block;
  }
</style>