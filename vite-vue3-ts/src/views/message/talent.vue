<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
  .talk-page{
    width: 100%;
    background: #f3f3f3;
    height: calc(100vh - 46px - 2.6rem);
    overflow: auto;
  }
  dl{
    padding: 0.96rem 0.64rem;
  }
  dl dt{
    overflow: hidden;
  }
  dl dt h5{
    font-size: 0.64rem;
    line-height: 0.64rem;
    font-weight: 300;
    color: #999999;
    text-align: center;
    margin-bottom: 0.69rem;
  }
  dl dt div{
    display: flex;
  }
  dl dt img{
    width: 2.14rem;
    height: 2.14rem;
    border-radius: 50%;
    margin-right: 0.64rem;
  }
  dl dt p{
    width: 12.53rem;
    background: #FFFFFF;
    border: 1px solid #EFEFEF;
    border-radius: 0.11rem;
    padding: 0.4rem 0.69rem;
    margin-bottom: 1.47rem;
  }
  dl dt.active div{
    display: block;
  }
  dl dt.active img{
    float: right;
    margin-right:0;
    margin-left:0.64rem;
  }
  dl dt.active p{
    float: right;
    font-size: 0.75rem;
    font-weight: 300;
    color: #FFFFFF;
    border: 1px solid #FF9415;
    background: #FF9415;
    border-radius: 0.13rem;
    position: relative;
  }
  .talk-bottom{
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100vw;
    background: #ffffff;
    text-align: center;
    z-index: 1;
    border-top: 1px solid #eeeeee;
  }
  .talk-input{
    display: flex;
    align-items: center;
    height: 2.6rem;
  }
  .talk-input span{
    width: 2.61rem;
    height: 1.33rem;
    line-height: 1.33rem;
    background: #FF9415;
    border-radius: 0.13rem;
    font-size: 0.64rem;
    font-weight: 100;
    text-align: center;
    color: #FFFFFF;
    margin-left: 0.59rem;
  }
  .talk-input span:last-child{
    margin: 0 0.59rem 0 0;
  }
  .talk-input input{
    flex: 1;
    height: 1.8rem;
    background: #FBFBFB;
    border: 1px solid #EFEFEF;
    border-radius: 0.13rem;
    padding: 0 0.5rem;
    margin: 0 0.4rem 0 0.5rem;
  }
  .talk-input i{
    font-size: 1.36rem;
    margin-right: 0.4rem;
  }
</style>