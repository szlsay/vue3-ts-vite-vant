<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .task-contract-tab{
        display: flex;
    }
    .task-contract-tab span{
        flex: 1;
        font-size: 0.75rem;
        font-weight: 400;
        color: #666666;
        line-height: 0.75rem;
        text-align: center;
        padding: 0.59rem 0;
        border-bottom: 1px solid  #EEEEEE;
        position: relative;
    }
    .task-contract-tab span i{
        width: 1.63rem;
        height: 0.05rem;
        background: #ffffff;
        position: absolute;
        bottom: 0px;
        left: 50%;
        margin-left: -0.815rem;
    }
    .task-contract-tab span.active i{
        background: #FF9415;
    }
    .task-contract-list{
        width: 100%;
        height: calc(100vh - 7.5rem);
    }
    .task-contract-item{
        padding: 1.63rem 0.59rem 1.43rem;
        border-bottom: 1px solid #eeeeee;
    }
    h2{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 0 0.48rem;
    }
    h2 label{
        font-size: 0.85rem;
        line-height: 0.85rem;
        font-weight: 400;
        color: #333333;
    }
    h2 span{
        font-size: 0.75rem;
        line-height: 0.75rem;
        font-weight: 400;
        color: #FF9415;
    }
</style>
