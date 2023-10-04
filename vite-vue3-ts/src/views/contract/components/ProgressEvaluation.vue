<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .wy-submit{
        position: static;
    }
    .eval-field{
        border: 1px solid #D5D3D3;
        margin-bottom: 1.49rem;
    }
    .eval-cont{
        padding: 1.28rem 0.56rem;
    }
    h3{
        font-size: 0.8rem;
        line-height: 0.8rem;
        font-weight: 500;
        color: #333333;
        margin-bottom: 0.88rem;
    }
    p{
        display: flex;
        justify-content: space-between;
        margin-bottom: 0.8rem;
    }
    p span{
        width: 5.92rem;
        height: 1.41rem;
        text-align: center;
        line-height: 1.41rem;
    }
    p span:nth-child(1){
        background: #ffffff;
        border: 1px solid #50D400;
        color:#50D400;
    }
    p span:nth-child(1).active{
        background: #50D400;
        color:#ffffff;
    }
    p span:nth-child(2){
        background: #ffffff;
        border: 1px solid #FE9215;
        color: #FE9215;
    }
    p span:nth-child(2).active{
        background: #FE9215;
        color:#ffffff;
    }
    p span:nth-child(3){
        background: #ffffff;
        border: 1px solid #FF0000;
        color: #FF0000;
    }
    p span:nth-child(3).active{
        background: #FF0000;
        color:#ffffff;
    }
</style>