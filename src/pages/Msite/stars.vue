<!-- 组件说明 -->
<template>
    <div class='stars'>
        <!-- 0-1.5分 -->
        <div class="n1">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div>
        <!-- 1.5-2 -->
        <!-- <div class="n1" v-if="1.5<=pingfen<2">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_half@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 2-2.5-->
        <!-- <div class="n1" v-if="2<=pingfen<2.5">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 2.5-3 -->
        <!-- <div class="n1" v-if="2.5<=pingfen<3">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_half@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 3-3.5 -->
        <!-- <div class="n1" v-if="3.5<=pingfen<4">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_off@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 3.5-4 -->
        <!-- <div class="n1" v-if="4<=pingfen<4.5">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_half@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 4-4.5 -->
        <!-- <div class="n1" v-if="4.5<=pingfen">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_off@2x.png">
        </div> -->
        <!-- 4.5-5 -->
        <!-- <div class="n1" v-if="pingfen<1.5">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_half@2x.png">
        </div> -->
        <!-- 5 -->
        <!-- <div class="n1" v-if="pingfen<1.5">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
            <img src="./images/stars/star24_on@2x.png">
        </div> -->
    </div>
</template>

<script>
    //import x from ''
export default {
        props:['pingfen'],
        components: {

        },
        data () {
            return {

            };
        },
        computed: {

        },
        methods: {

        },
}
</script>

<style scoped>
.stars{
    width: 75px;
    height: 15px;
}
.stars img{
    width: 10px;
    line-height: 15px;
}
</style>