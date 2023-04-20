<!-- 组件说明 -->
<template>
    <div class='footer_guide'>
        <a href="javascript:;" class="guide_item" :class="{on:'/msite'===$route.path}" @click="goTo('/msite')">
            <span class="item_icon">
                <i class="iconfont icon-zhuye"></i>
            </span>
            <span class="title">外卖</span>
        </a>
        <a href="javascript:;" class="guide_item" :class="{on:'/search'===$route.path}" @click="goTo('/search')">
            <span class="item_icon">
                <i class="iconfont icon-sousuo"></i>
            </span>
            <span class="title">搜索</span>
        </a>
        <a href="javascript:;" class="guide_item" :class="{on:'/order'===$route.path}" @click="goTo('/order')">
            <span class="item_icon">
                <i class="iconfont icon-dingdan"></i>
            </span>
            <span class="title">订单</span>
        </a>
        <a href="javascript:;" class="guide_item" :class="{on:'/profile'===$route.path}" @click="goTo('/profile')">
            <span class="item_icon">
                <i class="iconfont icon-wode"></i>
            </span>
            <span class="title">我的</span>
        </a>
    </div>
</template>

<script>
    //import x from ''
    export default {
        methods:{
            goTo(path){
                this.$router.replace(path)
            }
        }
    }
</script>

<style scoped>
.footer_guide{
    width: 100%;
    height: 8%;
    position: fixed;
    left: 0;
    bottom: 0;
    border-top: 1px solid rgb(222, 225, 230);
    display: flex;
    justify-content: space-around;
}
.guide_item{
    padding: 3% 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}
.on{
    color: rgb(100, 198, 255);
}
.iconfont{
    font-size: 130%;
}


</style>