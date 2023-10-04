<script setup lang="ts">

</script>

<template>
  <div>
    登录页
  </div>
</template><style scoped>
dl{
    font-size: 0.69rem;
    color: #666666;
}
dl dd{
    display: flex;
    align-items: center;
    border-bottom: 1px solid #eeeeee;
    padding: 0.85rem 0.93rem;
    margin-bottom: 1rem;
}
dl dd img{
    width: 2.67rem;
    height: 2.67rem;
    border-radius: 50%;
    margin-right: 0.75rem;
}
dl dd h5{
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-weight: 300;
    color: #333333;
    margin-bottom: 0.48rem;
}
dl dd p{
    color: #333333;
    line-height: 0.69rem;
}
dl dt{
    display: flex;
    margin-bottom: 1rem;
    padding: 0 0.72rem 0 0.56rem;
}
dl dt label{
    flex: 1;
}
dl dt span{
    text-align: right;
    color: #000000;
}
.contract-btn{
    position: fixed;
    bottom: 0.64rem;
    left: 0rem;
    width: 100%;
    display: flex;
}
.contract-btn button{
    height: 2.35rem;
    line-height: 2.23rem;
    border: 1px solid #FF9415;
    border-radius: 0.27rem;
    flex: 1;
    font-size: 0.8rem;
    text-align: center;
    margin-right: 0.64rem;
}
.contract-btn button:first-child{
    margin-left: 0.64rem;
}
.contract-btn button.refuse-btn{
    color: #FF9415;
    background: #ffffff;
}
.contract-btn button.confirm-btn{
    color: #ffffff;
    background: #FF9415;
}
.small-item-text h3{
    font-size: 0.96rem;
    line-height: 0.96rem;
    font-weight: 300;
    color: #333333;
    margin-bottom: 0.48rem;
}
.small-item-text h3 i{
    width: 1.97rem;
    height: 0.85rem;
    line-height: 0.85rem;
    display: inline-block;
    background: linear-gradient(90deg, #FEA829, #FE8F27);
    border-radius: 1.5rem 1rem 1rem 1rem;
    font-size: 0.59rem;
    font-weight: normal;
    color: #FFFFFF;
    font-style: normal;
    text-align: center;
    margin-left: 0.64rem;
}
.small-item-text p{
    font-size: 0.69rem;
    line-height: 0.69rem;
    font-weight: 100;
    color: #333333;
}
</style>