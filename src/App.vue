<template>
  <div>
    <!-- 使用 -->
    <Header></Header>
    <Footer></Footer>
  </div>
</template>

<script>
// 导入，引入
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  name:'App',
  components:{
    // 注册
    Header,
    Footer
  }
}
</script>

<style>

</style>
