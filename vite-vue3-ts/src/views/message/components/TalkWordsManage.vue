<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
>>> .van-swipe-cell__right{
    display: flex;
    align-items: center;
}
.item{
    margin: 0 0.72rem;
    border-bottom: 1px solid #eeeeee;
}
.item p{
    font-size: 0.75rem;
    font-weight: 300;
    color: #030303;
    line-height: 1.12rem;
    padding: 1rem 0.2rem 0.4rem;
    text-align: left;
}
.item div{
    display: flex;
    align-items: center;
    justify-content: flex-end;
    margin-bottom: 0.77rem;
}
.item div span{
    font-size: 0.75rem;
    line-height: 0.75rem;
    font-weight: 300;
    color: #030303;
    text-align: right;
}
.item div img{
    width: 0.91rem;
    height: 0.91rem;
}
.delete{
    width: 1.87rem;
    height: 1.87rem;
    margin-right: 0.64rem;
}
.add{
    height: 2.35rem;
    background: linear-gradient(90deg, #FFA400, #FF8900);
    border-radius: 0.27rem;
    line-height: 2.35em;
    position: fixed;
    border: none;
    bottom: 0.64rem;
    margin: 0 0.64rem;
    font-size: 0.8rem;
    font-weight: 400;
    color: #FFFFFF;
    width: calc(100vw - 1.28rem);
    left: 0;
}
</style>