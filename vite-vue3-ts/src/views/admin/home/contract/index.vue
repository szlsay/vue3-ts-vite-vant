<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .admin-contract-popup{
        padding: 1.4rem 1rem;
    }
    .admin-contract-popup h5{
        font-size: 0.85rem;
        line-height: 0.85rem;
        margin-bottom: 0.8rem;
        font-weight: 400;
        color: #333333;
        text-align: center;
    }
    .admin-contract-popup p{
        font-size: 0.8rem;
        font-weight: 400;
        color: #333333;
        line-height: 1.28rem;
        text-align: center;
        margin-bottom: 0.76rem;
    }
    .admin-contract-popup button{
        width: 10.99rem;
        height: 1.92rem;
        background: #FE9215;
        border: 0px solid #FF6F00;
        border-radius: 0.16rem;
        font-size: 0.85rem;
        line-height: 1.92rem;
        text-align: center;
        font-weight: 400;
        color: #FFFFFF;
        border: none;
    }
    .home-contract-bottom{
        border-top: 1px solid #F5F5F5;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding:0.6rem 0 0 0.2rem;
    }
    .home-contract-bottom div{
        width: 8rem;
    }
    .home-contract-bottom div.orange i{
        background: #FE9215;
    }
    .home-contract-bottom div.orange span{
        color: #FE9215;
    }
    .home-contract-bottom div.red i{
        background: #FF0000;
    }
    .home-contract-bottom div.red span{
        color: #FF0000;
    }
    .home-contract-bottom div i{
        width: 0.37rem;
        height: 0.37rem;
        background: #50D400;
        border-radius: 50%;
        display: inline-block;
    }
    .home-contract-bottom div span{
        font-size: 0.64rem;
        line-height: 0.64rem;
        font-weight: 400;
        color: #50D400;
        margin-left: 0.32rem;
    }
    .home-contract-bottom button{
        width: 4rem;
        height: 1.39rem;
        background: #FE9215;
        border-radius: 0.16rem;
        font-size: 0.69rem;
        line-height: 1.39rem;
        text-align: center;
        font-weight: 100;
        color: #FFFFFF;
        border: none;
    }
    .wy-admin-page{
        background: #f6f6f6;
        height: 100vh;
        overflow: auto;
    }
    .wy-flex{
        display: flex;
        align-items: center;
    }
    .home-contract-list{
        background: #FFFFFF;
        border-radius: 0.53rem;
        margin: 0 0.59rem 0.53rem;
        padding: 0.88rem 0.48rem 0.64rem;
    }
    .contract-progress{
        flex: 1;
    }
    dl{
    }
    dl dt{
        margin-bottom: 0.51rem;
    }
    dl dt h3{
        font-size: 0.91rem;
        font-family: PingFang SC;
        font-weight: 400;
        color: #333333;
        line-height: 0.91rem;
        margin-bottom: 0.83rem;
    }
    dl dt label{
        font-size: 0.69rem;
        line-height: 0.69rem;
        font-weight: 300;
        color: #666666;
    }
    dl dt span{
        font-size: 0.69rem;
        line-height: 0.69rem;
        font-weight: 300;
        color: #333333;
    }
</style>