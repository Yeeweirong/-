<template>
  <div>
      <Header></Header>
      <router-view></router-view>
      <Footer v-show="$route.meta.show"></Footer>
  </div>


</template>

<script>

// 引入
import Header from './components/Header'
import Footer from './components/Footer'

export default {
  name: '',
  components:{
    Header,
    Footer
  }

}
</script>

<style scoped>

</style>
