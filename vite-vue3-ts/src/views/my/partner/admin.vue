<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template>
<style scoped>
>>>.van-radio__icon--checked .van-icon{
    background-color:#FE9527;
    border-color: #FE9527;
}
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
    background: url('@/assets/img/my/partner/admin-bg-top.png') no-repeat;
    height: 19.04rem;
    width: 100%;
    background-size: 100%;
}
.admin-adv{
    background: url('@/assets/img/my/partner/admin-bg-center.png') no-repeat;
    background-size: 100%;
    position: relative;
    top: -2rem;
    height: 24.53rem;
}
.company-top h3{
    font-size: 2.45rem;
    line-height: 2.45rem;
    font-family: Lantinghei SC;
    font-weight: 800;
    font-style: italic;
    color: #FFFFFF;
    text-align: center;
    padding:3.68rem 0 0.91rem;
}
.company-top h4{
    font-size: 1.68rem;
    line-height: 1.68rem;
    font-family: PingFang SC;
    font-weight: 600;
    font-style: italic;
    color: #FFFFFF;
    text-align: center;
}
h5{
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-family: PingFang SC;
    font-weight: 400;
    color: #FFFFFF;
    margin-bottom: 1.2rem;
    text-align: center;
    position: relative;
    padding-top: 0.5rem;
}
.company-page{
    background: linear-gradient(90deg, #035BDB, #1373FD, #0051C7);
    padding:0.48rem;
}
.company-adv{
    font-size: 0.8rem;
    font-family: PingFang SC;
    font-weight: 400;
    color: #0152C9;
    line-height: 1.28rem;
    padding: 0.8rem 1.87rem 0.3rem;
}
dl{

}
dl dd{
    border-bottom: 1px solid #BED0DD;
    display: flex;
    align-items: center;
    padding: 0.64rem 0;
    margin: 0 1.12rem;
}
dl dd:last-child{
    border-bottom: 0;
}
dl dd span{
    width: 3.12rem;
    height: 3.12rem;
    line-height: 3.12rem;
    text-align: center;
    background: #2C92FF;
    border-radius: 50%;
    font-size: 0.96rem;
    font-family: PingFang SC;
    font-weight: 500;
    color: #FFFFFF;
}
dl dd p{
    font-size: 0.69rem;
    font-family: PingFang SC;
    font-weight: 300;
    color: #000000;
    line-height: 0.96rem;
    flex: 1;
    margin-left: 0.45rem;
}
.company-settled{
    background: url('@/assets/img/my/partner/admin-bg-bottom.png') no-repeat;
    background-size: 100%;
    padding: 0.1rem 0.8rem;
    margin-top: -1.5rem;
    height: 56.77rem;
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
    background: #4E90EF;
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