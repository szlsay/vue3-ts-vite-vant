<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .wy-admin-page{
        background: #f6f6f6;
        height: 100vh;
        overflow: auto;
    }
    .auditor-flex{
        display: flex;
        align-items: center;
    }
    .auditor-flex-right{
        flex: 1;
    }
    .auditor-flex img{
        width: 2.67rem;
        height: 2.67rem;
        border-radius: 50%;  
        margin-right: 0.8rem;
    }
    dl{
        background: #FFFFFF;
        border-radius: 0.53rem;
        margin: 0 0.59rem 0.53rem;
        padding: 0.88rem 0.48rem 0.64rem;
    }
    dt{
        margin-bottom: 0.48rem;
        white-space: nowrap;
        text-overflow: ellipsis;
        overflow: hidden;
    }
    dt h3{
        font-size: 0.91rem;
        line-height: 0.91rem;
        font-weight: 400;
        color: #333333;
        margin-bottom: 0.4rem;
    }
    dt h3 i{
        font-style: normal;
        font-size: 0.64rem;
        line-height: 0.64rem;
        font-weight: 400;
        color: #FE9215;
        float: right;
    }
    dt label{
        font-size: 0.69rem;
        line-height: 0.69rem;
        font-weight: 300;
        color: #666666;
    }
    dt span{
        font-size: 0.69rem;
        line-height: 0.69rem;
        font-weight: 300;
        color: #333333;
    }
    dd{
        border-top: 1px solid #F5F5F5;
        overflow: hidden;
        padding: 0.53rem 0rem 0 0;
        margin-top: 0.68rem;
    }
    dd button{
        border: none;
        width: 4rem;
        height: 1.39rem;
        background: #FE9215;
        border-radius: 0.16rem;
        font-size: 0.69rem;
        font-weight: 100;
        color: #FFFFFF;
        text-align: center;
        float: right;
    }
</style>