<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
  >>>.van-nav-bar__content{
    background: #FF8E00;
  }
  >>>.van-nav-bar__title,>>>.van-icon-arrow-left:before{
    color: #ffffff;
  }
  .van-hairline--bottom:after{
    border: 0;
  }
  .detail-page{
    margin: 0.53rem;
    padding-bottom: 2rem;
  }
.task-detail-footer{
    display: flex;
    position: fixed;
    left: 0;
    width: 100%;
    align-items: center;
    background: #ffffff;
    bottom: 0;
    padding: 0.64rem 0;
}
.task-detail-footer button{
    margin-right: 0.64rem;
}
.task-detail-footer .active >>> .van-icon-star-o:before{
    color: #FE8F27;
}
</style>