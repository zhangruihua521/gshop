<template>
  <div id="app">
    <router-view></router-view>
    <!-- 底部组件 -->
    <Foolter v-show="$route.meta.showFooter"></Foolter>
      <!-- <mt-button>按钮</mt-button> -->
  </div>
</template>
<script>
import Foolter from './components/Foolter/Foolter'
export default {
  components:{
    Foolter
  }
}
</script>
<style lang="stylus">

</style>
