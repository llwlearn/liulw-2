<template>
    <div>

        <ul class="layui-nav layui-nav-tree" lay-filter="test">
            <!-- 侧边导航: <ul class="layui-nav layui-nav-tree layui-nav-side"> -->
            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第一课：句子成分</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('1_1')">1、主语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_2')">2、谓语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_3')">3、表语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_4')">4、宾语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_5')">5、宾语补足语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_6')">6、状语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_7')">7、定语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_8')">8/同位语</a></dd>
                    <dd><a href="#" @click="zhu_ti('1_9')">9、九个基本句型</a></dd>
                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第二课：名词</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('2_1')">1、名词的定义</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_2')">2、名词的分类</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_3')">3、可数名词单数变复数</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_4')">4、可数名词不规则变化</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_5')">5、不可数名词</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_6')">6、名词的作用</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_7')">7、名词所有格</a></dd>
                    <dd><a href="#" @click="zhu_ti('2_8')">8、附录</a></dd>

                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第三课：代词</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('3_1')">1、人称代词</a></dd>
                    <dd><a href="#" @click="zhu_ti('3_2')">2、物主代词</a></dd>
                    <dd><a href="#" @click="zhu_ti('3_3')">3、指示代词</a></dd>
                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第四课：形容词</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('4_1')">1、形容词的定义</a></dd>
                    <dd><a href="#" @click="zhu_ti('4_2')">2、形容词的用法</a></dd>
                    <dd><a href="#" @click="zhu_ti('4_3')">3、形容词的位置</a></dd>
                    <dd><a href="#" @click="zhu_ti('4_4')">4、比较级和最高级</a></dd>
                    <dd><a href="#" @click="zhu_ti('4_5')">5、比较级和最高级用法</a></dd>
                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第五课：动词</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('5_1')">1、(非)谓语动词</a></dd>
                    <dd><a href="#" @click="zhu_ti('5_2')">2、实义动词</a></dd>
                    <dd><a href="#" @click="zhu_ti('5_3')">3、实义动词的五种形式</a></dd>
                    <dd><a href="#" @click="zhu_ti('5_4')">4、系动词</a></dd>
                    <dd><a href="#" @click="zhu_ti('5_5')">5、助动词</a></dd>
                    <dd><a href="#" @click="zhu_ti('5_6')">6、情态动词</a></dd>
                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第六课：冠词</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('6_1')">1、不定冠词的用法</a></dd>
                    <dd><a href="#" @click="zhu_ti('6_2')">2、定冠词the的用法</a></dd>
                    <dd><a href="#" @click="zhu_ti('6_3')">3、不使用冠词的场合</a></dd>
                    <dd><a href="#" @click="zhu_ti('6_4')">4、用冠词和不用冠词</a></dd>
                </dl>
            </li>

            <li class="layui-nav-item layui-nav-itemed">
                <a href="javascript:;">第七课：一般现在时态</a>
                <dl class="layui-nav-child">
                    <dd><a href="#" @click="zhu_ti('7_1')">什么是时态</a></dd>
                    <dd><a href="#" @click="zhu_ti('7_2')">1、主语+系动词+表语</a></dd>
                    <dd><a href="#" @click="zhu_ti('7_3')">2、主语+谓语+宾语</a></dd>
                    <dd><a href="#" @click="zhu_ti('7_4')">3、时间状语</a></dd>
                </dl>
            </li>

        </ul>

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
div ul li dl dd a {
    background-color: #696969;

}
</style>