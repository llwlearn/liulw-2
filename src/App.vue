<template>

    <div>
        <!-- Head -->
        <div>

            <Head></Head>
        </div>
        <!-- Up -->
        <div>
            <Up></Up>
        </div>

        <div class="layui-container layui-row" style="width: 1239px;">
            <!-- Navigation -->
            <div>
                <Navigation></Navigation>
            </div>

            <!-- Body -->
            <div id="Body">

                <div class="layui-col-xs2 layui-col-sm2 layui-col-md2">
                    <Sidebar></Sidebar>
                </div>

                <div class="layui-col-xs8 layui-col-sm8 layui-col-md8">
                    <Conten></Conten>
                </div>

                <div class="layui-col-xs2 layui-col-sm2 layui-col-md2">
                    <Tool></Tool>
                </div>

            </div>

        </div>

    </div>

</template>

<script>
// 头部
import Head from '@/components/Head.vue'
// 导航栏
import Navigation from '@/components/Navigation.vue'
// 侧边栏
import Sidebar from '@/components/Sidebar.vue';
// 内容
import Conten from '@/components/Conten.vue';
// 工具箱
import Tool from '@/components/Tool.vue';
// 回到顶部
import Up from '@/components/Up.vue';

export default {
    components: {
        Head,
        Navigation,
        Sidebar,
        Conten,
        Tool,
        Up,
    }
}

</script>

<style>
body {
    background-color: #ffffff;
}

#Body {
    background-color: #eeeeee;
    display: inline-block;
    width: 100%;
}

#Body div:nth-child(0) {
    height: 100%;
    background-color: blue;
}
</style>