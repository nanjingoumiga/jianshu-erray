<template>
  <div>
    <h1>注册</h1> 
  </div>
</template>

<script>
import axios from '~/plugins/axios'

export default {
  head: {
    title: '注册 - 简书',
    meta: [
      { charset: 'utf-8' },
      { name: 'keywords', content:'注册页面' },
      { name: 'description', content: '注册简书' },
      { name: 'author', content: '陈佳威' }
    ]
  },
  data () {
    return{
      name:'注册'
    }
  }
}
</script>

<style scoped>

</style>