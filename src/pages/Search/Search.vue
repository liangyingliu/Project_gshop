<!-- 组件说明 -->
<template>
    <div class='search'>
        <div class="head">
            <span>搜索</span>
        </div>
        <div class="main">
            <input type="text" placeholder="请输入商家或美食名称">
            <button type="submit">提交</button>
        </div>
        <div class="foot"></div>
    </div>
</template>

<script>
    //import x from ''
    export default {
        components: {
        },
    }
</script>

<style scoped>

.head{
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
.head span{
    color: white;
}
.main{
    width: 100%;
    height: 8%;
    display: flex;
    justify-content: space-evenly;
    position: absolute;
    top: 8%;
    background-color:white;
    padding-top: 12px;
    padding-bottom: 12px;
    
}
.main input{
    width: 75%;
    height: 60%;
    outline: none;
    background-color: rgb(245, 245, 245);
}
.main button{
    width: 20%;
    height: 60%;
    background-color: rgb(100, 198, 255);
    border: none;
    color: white;
    font-size: large;
}
.foot{
    width: 100%;
    height: 78%;
    position: absolute;
    top: 16%;
    background-color: rgb(245, 245, 245);
}
</style>