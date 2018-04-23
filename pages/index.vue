<template>
  <div>
    <div style="height:100%">
      <my-header></my-header>
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
              show3: true
            };
        },
    };
</script>

<style scoped>
.transition-box {
    margin-bottom: 10px;
    width: 200px;
    height: 100px;
    border-radius: 4px;
    background-color: #409EFF;
    text-align: center;
    color: #fff;
    padding: 40px 20px;
    box-sizing: border-box;
    margin-right: 20px;
  }
</style>
