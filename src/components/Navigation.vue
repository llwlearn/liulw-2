<template>
    <div>

        <ul class="layui-nav dao-hang" lay-filter="">
            <li class="layui-nav-item"><a href="">猜你喜欢</a></li>
            <li class="layui-nav-item layui-this"><a href="">主页</a></li>
            <li class="layui-nav-item"><a href="">动态</a></li>
            <li class="layui-nav-item"><a href="">社区</a></li>
            <li class="layui-nav-item"><a href="javascript:;">关于</a>
                <dl class="layui-nav-child">
                    <!-- 二级菜单 -->
                    <dd><a href="">帮助</a></dd>
                    <dd><a href="">网站介绍</a></dd>
                    <dd><a href="">客服</a></dd>
                </dl>
            </li>
        </ul>

    </div>
</template>
<script>
//注意：导航 依赖 element 模块，否则无法进行功能性操作
layui.use('element', function () {
    var element = layui.element;
});
</script>

<style>
.dao-hang {
    margin-top: 10px;
    margin-bottom: 10px;
}
</style>