<!-- 组件说明 -->
<template>
    <div class='msite'>
        <div class="msite_head">
            <span class="head_search">
                <i class="iconfont icon-sousuo1" @click="goTo('/search')"></i>
            </span>
            <span class="head_site">广东省深圳市龙华区</span>
            <span class="head_login">
                <span>登录|注册</span>
            </span>
        </div>
        <div class="msite_nav">
            <div class="swiper">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/1.jpg">
                            </div>
                            <span>甜品饮品</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/2.jpg">
                            </div>
                            <span>商超便利</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/3.jpg">
                            </div>
                            <span>美食</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/4.jpg">
                            </div>
                            <span>简餐</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/5.jpg">
                            </div>
                            <span>新店特惠</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/6.jpg">
                            </div>
                            <span>准时达</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/7.jpg">
                            </div>
                            <span>预定早餐</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/8.jpg">
                            </div>
                            <span>土豪推荐</span>
                        </a>
                    </div>
                    <div class="swiper-slide">
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/9.jpg">
                            </div>
                            <span>甜品饮品</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/10.jpg">
                            </div>
                            <span>商超便利</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/11.jpg">
                            </div>
                            <span>美食</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/12.jpg">
                            </div>
                            <span>简餐</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/13.jpg">
                            </div>
                            <span>新店特惠</span>
                        </a>
                        <a href="" class="nav_item">
                            <div class="food_container">
                                <img src="./images/nav/14.jpg">
                            </div>
                            <span>准时达</span>
                        </a>
                    </div>
                </div>
                <div class="swiper-pagination"></div>
            </div>
        </div>
        <div class="msite_foot">
            <span class="head">
                <i class="iconfont icon-liebiao2"></i>
                <span>附近商家</span>
            </span>
            <div class="food">
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
                <div class="food_item">
                    <div class="photo">
                        <img src="./images/shop/1.jpg">
                    </div>
                    <div class="info">
                        <div class="shang">
                            <jinpai></jinpai>
                            <h3 class="title">锄禾日当午，汗滴禾下土</h3>
                            <ul>
                                <li>保</li>
                                <li>准</li>
                                <li>票</li>
                            </ul>
                        </div>
                        <div class="zhong">
                            <stars class="stars" :pingfen='4.1'></stars>
                            <span class="pingfen">4.1</span>
                            <span class="yueshou">月售106单</span>
                            <zhuansong class="zhuansong"></zhuansong>
                        </div>
                        <div class="xia">
                            <span>￥20起送 / 配送费约5元</span>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
import Swiper from 'swiper'
import 'swiper/swiper.min.css'
import jinpai from './jinpai.vue'
import zhuansong from './zhuansong.vue'
import stars from './stars.vue'

export default {
    mounted() {
        new Swiper('.swiper', {
            loop: false, 
            pagination: {
                el:'.swiper-pagination',
              }
            })
        },
    components: {
        jinpai,
        zhuansong,
        stars
    },
    methods: {
        goTo(path) {
                this.$router.replace(path)
            }
        }
    }
</script>

<style scoped>
.msite{
    width: 100%;
    height: 92%;
    position: fixed;
    top: 0;
    left: 0;
}
.msite_head{
    width: 100%;
    height: 8%;
    position: fixed;
    top: 0;
    left: 0;
    background-color: rgb(100, 198, 255);
    display: flex;
    justify-content: space-around;
    line-height: 400%;
}
.head_search i{
    font-size: 150%;
    color: white;
}
.msite_head span{
    color: white;
}
.head_site{
    width: 40%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}
.msite_nav{
    width: 100%;
    height: 25%;
    position: fixed;
    top: 8%;
    left: 0;
    display: block;
    border-bottom: 1px solid rgb(222, 225, 230);
}
.msite_nav .swiper-slide{
    width: 100%;
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    text-align: center;
}
.msite_nav a{
    padding: 5% 0;
    display: block;
    width: 25%;
    height: 50%;
}
.msite_nav img{
    width: 50%;
}
.msite_foot{
    width: 100%;
    height: 59%;
    position: fixed;
    top: 33%;
    left: 0;
}
.msite_foot .head{
    display: block;
    width: 100%;
    height: 5%;
    padding-top: 3%;
    padding-left: 2%;
}
.msite_foot .head i{
    color: black;
    font-weight: bold;
}
.food{
    width: 100%;
    height: 93%;
    overflow: auto;
}
.food .photo img{
    width: 100px;
}
.food_item {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    padding-bottom: 5px;
    margin-top: 5px;
    border-bottom: 1px solid rgb(222, 225, 230);
}
.info{
    width: 250px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-left: 8px;
}
.info .shang{
    display: flex;
    flex-direction: row;
    position: relative;
}
.shang h3{
    display: block;
    height: 20px;
    width: 120px;
    font-weight: bold;
    line-height: 20px;
    padding-left: 5px;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}
.shang ul{
    position: absolute;
    right: 10px;
}
.shang ul li{
    font-size: 17px;
    display: inline-block;
    border-radius: 10%;
    border: 1px solid rgb(198, 198, 198);
    color: rgb(198, 198, 198);
}
.zhong{
    margin-top: 30px;
    display: flex;
    position: relative;
}
.pingfen{
    height: 15px;
    color: rgb(234, 126, 74);
    font-size: 10px;
    font-weight: bold;
    line-height: 15px;
}
.yueshou{
    height: 15px;
    font-size: 10px;
    color: rgb(198, 198, 198);
    margin-left: 8px;
    line-height: 15px;
}
.zhuansong{
    position: absolute;
    right: 10px;
}
.xia{
    width: 100%;
    height: 18%;
}
.xia span{
    font-size: 13px;
}
</style>