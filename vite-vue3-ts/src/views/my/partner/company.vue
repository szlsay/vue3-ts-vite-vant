<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
>>>.van-cell:first-child .van-field__label{
    width: 5rem;
}
>>>.van-cell .van-field__label{
    width: 3.5rem;
}
.field-last{
    display: block;
}
.field-last >>>.van-field__label{
    margin-bottom: 1rem;
}
.company-top{
    background: url('@/assets/img/my/partner/company-bg-top.png') no-repeat;
    height: 20rem;
    width: 100%;
    background-size: 100%;
}
.company-top h3{
    font-size: 2.45rem;
    line-height: 2.45rem;
    font-weight: 800;
    color: #FFFFFF;
    text-align: center;
    padding:3.68rem 0 0.96rem;
}
.company-top h4{
    font-size: 1.28rem;
    line-height: 1.28rem;
    font-weight: 600;
    color: #FFFFFF;
    text-align: center;
}
h5{
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-family: Lantinghei SC;
    font-weight: 600;
    color: #FD4919;
    background: #FFE28A;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 1.2rem;
    position: relative;
}
h5::after{
    position: absolute;
    width: 1.26rem;
    height: 0.13rem;
    background: linear-gradient(180deg, #FFE28A, #FA7911);
    content: '';
    left: 0.1rem;
    top: 1.2rem;
}
.company-page{
    background: #F03C17;
    padding:0.8rem;
}
.company-adv{
    background: #FFFFFF;
    box-shadow: 0rem 0rem 0rem 0rem rgba(247,93,16,0.17);
    border-radius: 0.52rem;
    font-size: 0.8rem;
    font-family: PingFang SC;
    font-weight: 400;
    color: #F03C17;
    line-height: 1.28rem;
    padding:0.8rem;
    margin: 0 0 1.23rem;
}
.company-service{
    background: #FFFFFF;
    box-shadow: 0rem 0rem 0rem 0rem rgba(247,93,16,0.17);
    border-radius: 0.52rem;
    padding: 1.3rem 0.5rem;
    margin-bottom: 1.8rem;
}
.company-service img{
    width: 100%;
}
.company-settled{
    background: #FFFFFF;
    box-shadow: 0rem 0rem 0rem 0rem rgba(247,93,16,0.17);
    border-radius: 0.52rem;
    padding: 0.8rem;
}
.wy-radio{
    padding: var(--van-cell-vertical-padding) var(--van-cell-horizontal-padding);
    position: relative;
    color: var(--van-cell-text-color);
    font-size: var(--van-cell-font-size);
}
.company-p{
    color: var(--van-cell-text-color);
    font-size: var(--van-cell-font-size);
    padding: 1.2rem var(--van-cell-horizontal-padding) 0.8rem;
}
.wy-radio label{
    margin-bottom: 0.8rem;
    display: block;
}
.wy-radio:after {
    position: absolute;
    box-sizing: border-box;
    content: " ";
    pointer-events: none;
    right: var(--van-padding-md);
    bottom: 0;
    left: var(--van-padding-md);
    border-bottom: 1px solid var(--van-cell-border-color);
    transform: scaleY(.5);
}
.company-tip{
    font-size: 0.64rem;
    font-weight: 100;
    color: #999999;
    line-height: 0.96rem;
    padding: 1.2rem var(--van-cell-horizontal-padding) 0.8rem;
}
button{
    width: 13.8rem;
    height: 2.1rem;
    background: #F03C17;
    border-radius: 0.2rem;
    font-size: 0.8rem;
    font-family: PingFang SC;
    font-weight: 400;
    color: #FFFFFF;
    line-height: 2.1rem;
    text-align: center;
    border: 0;
    margin: 0.5rem auto;
    display: block;
}
</style>