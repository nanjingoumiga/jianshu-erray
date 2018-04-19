<template>
  <div>
      <p>Hello world</p>
    <div style="height:100%">
      <my-header></my-header>
      <p>我的主体部分</p>
    </div>
  </div>
</template>

<script>
import myHeader from '../components/myHeader';
export default {
  // 设置页面的标题以及描述,关键字等元信息
        head: {
            title: "简书 - 创作你的创作",
            meta: [
                { charset: "utf-8" },
                { name: "keywords", content: "简书首页" },
                { name: "description", content: "简书首页" },
                { name: "author", content: "陈佳威" }
            ]
        },
        components:{
          myHeader,
        },
        data() {
            return {
              name:'首页',
            };
        },
    };
</script>

<style scoped>

</style>
