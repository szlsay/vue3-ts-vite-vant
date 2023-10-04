<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
  .van-pull-refresh{
    height: calc(100vh - 46px - 5rem);
    overflow: auto;
  }
  .contract-tab{
    display: flex;
  }
  .contract-tab span{
    font-size: 0.75rem;
    line-height: 0.75rem;
    font-weight: 400;
    color: #666666;
    flex: 1;
    align-items: center;
    border-bottom: 1px solid #EEEEEE;
    padding: 0.59rem 0;
    text-align: center;
    position: relative;
  }
  .contract-tab span.active{
    color: #FF9415;
  }
  .contract-tab span.active i{
    width: 1.63rem;
    height: 0.05rem;
    background: #FF9415;
    position: absolute;
    bottom: 0px;
    left: 50%;
    margin-left: -0.815rem;
  }
</style>