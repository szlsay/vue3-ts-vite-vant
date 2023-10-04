<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
    .coupon-page{
        background: #f6f6f6;
        height: 100vh;
    }
    img{
        width: 100%;
        margin-bottom: 0.83rem;
    }
    dl{
        margin: 0 0.8rem;
        overflow: hidden;
    }
    dt{
        width: 18.4rem;
        height: 5.33rem;
        margin-bottom: 0.56rem;
        display: flex;
        position: relative;
        align-items: center;
        border-radius: 0.27rem;
        overflow: hidden;
    }
    dt strong{
        font-size: 1.28rem;
        font-weight: 500;
        color: #F19638; 
        display: block;
    }
    dt span{
        font-size: 0.59rem;
        font-weight: 400;
        color: #F19638;
        border: 1px solid #F19638;
        border-radius: 0.11rem;
        padding: 0 0.21rem;
    }
    dt h5{
        font-size: 0.8rem;
        line-height: 0.8rem;
        font-weight: 400;
        color: #282828;
        margin-bottom: 0.64rem;;
    }
    dt p{
        font-size: 0.64rem;
        line-height: 0.64rem;
        font-weight: 400;
        color: #909090;
    }
    dt i{
        position: absolute;
        border-bottom: 2rem solid #C9C9C9;
        border-radius: 0rem 0rem 0rem 0rem; 
        border-left: 2rem solid transparent;
        border-right: 2rem solid transparent;
        -webkit-transform: rotate(45deg);
        padding-left: 0px;
        right:-1.4rem;
        top:-0.4rem;
    }
    dt em{
        font-size: 0.56rem;
        font-weight: 400;
        color: #FFFFFF;
        position: absolute;
        top: 0.5rem;
        right: 0rem;
        -webkit-transform: rotate(45deg);
        padding-left: 0rem;
        font-style: normal;
    }
    .link strong,
    .link h5,
    .link p{
        color: #C4C4C4;
    }
    .link span{
        color: #999999;
        border-color: #999999;
    }
    .link{
        background: url(@/assets/img/my/coupon/list-link.png) no-repeat;
        background-size: 100%;
    }
    .active{
        background: url(@/assets/img/my/coupon/list-active.png) no-repeat;
        background-size: 100%;
    }
    .list-coupon-left{
        width: 29%;
        text-align: center;
    }
    .list-coupon-center{
        width: 49%;
        text-align: center;
    }
    .list-coupon-right{
        width: 22%;
    }
    button{
        width: 3.31rem;
        height: 1.23rem;
        background: #FF9415;
        border-radius: 0.61rem;
        border: 1px solid #FF9415;
        font-size: 0.64rem;
        color: #ffffff;
    }
    .btn-type-2{
        background: #ffffff;
        border: 1px solid #FF9415;
        color: #FF9415;
    }
    .btn-type-3{
        background: #ffffff;
        border: 1px solid #999999;
        color: #999999;
    }
</style>