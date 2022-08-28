<template>

    <div class="Head">
        <div class="layui-col-xs6 layui-col-sm6 layui-col-md2 layui-col-md-offset1">

            <a href="#" @click="zhu_ti('0')">
                <img src="@/assets/image/English.png" alt="" style="height: 90%;">
            </a>
        </div>

        <div class="layui-col-xs6 layui-col-sm6 layui-col-md2 layui-col-md-offset4">

            <input type="text" name="title" required lay-verify="required" placeholder="搜索......" autocomplete="off"
                class="layui-input">

        </div>

        <div class="layui-col-xs6 layui-col-sm6 layui-col-md2 layui-col-md-offset1">

            <button type="button" class="layui-btn ">登录</button>
            <button id="button" type="button" class="layui-btn layui-btn-normal">注册</button>


        </div>

    </div>

</template>

<script>

export default {
    methods: {
        zhu_ti(res) {
            $(".zhu-yao div").hide();
            $("#div" + res).show();
        }
    }
}

</script>

<style>
.Head {

    width: 100%;
    height: 70px;
    background-color: #393d49;
}

.Head div {
    height: 100%;
}

.Head div:nth-child(2) input,
.Head div:nth-child(3) button {
    display: inline-block;
}

.Head div:nth-child(2),
.Head div:nth-child(3) {
    line-height: 70px;
}
</style>