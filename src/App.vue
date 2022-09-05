<template>
  <div id="app">
   <MainHeader></MainHeader>
   <MainContent></MainContent>
   <SecondContent></SecondContent>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainContent from './components/MainContent.vue'
import SecondContent from './components/SecondContent.vue'

export default {
  name: 'App',
  components:{
    MainHeader,
    MainContent,
    SecondContent,
  },
 
}
</script>

<style lang="scss">
  @import './style/index.scss';
</style>
