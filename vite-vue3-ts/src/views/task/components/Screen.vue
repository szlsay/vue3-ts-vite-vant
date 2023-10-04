<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .task-screen{
        padding: 0 0.6rem;
    }
    .task-screen h3{
        font-size: 0.96rem;
        line-height: 0.96rem;
        font-weight: 500;
        color: #333333;
        margin: 0.8rem 0;
    }
    .task-screen span{
        width: 5.76rem;
        height: 1.6rem;
        line-height: 1.6rem;
        background: #F5F6F8;
        border: 1px solid #F5F6F8;
        border-radius: 0.16rem;
        font-size: 0.75rem;
        font-weight: 400;
        color: #666666;
        text-align: center;
        display: inline-block;
        margin: 0 0.59rem 0.51rem 0;
    }
    .task-screen span:nth-child(3n){
        margin-right: 0;
    }
    .task-screen span.active{
        color: #FF8A00;
        border: 1px solid #FE8F27;
        background: #ffffff;
    }
    .screen-footer{
        position: fixed;
        bottom: 0;
        background: #FFFFFF;
        box-shadow: 0rem 0rem 1rem 0rem rgba(208,208,208,0.39);
        padding: 0.83rem 0.64rem;
        display: flex;
        width: calc(100vw - 1.28rem);
    }
    .screen-clear{
        width: 5.33rem;
        height: 2.35rem;
        background: #F5F6F8;
        border-radius: 0.27rem;
        border: 0;
        font-size: 0.8rem;
        font-weight: bold;
        color: #666565;
        margin-right: 0.64rem;
    }
</style>