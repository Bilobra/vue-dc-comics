<template>
  <div id="app">
    <MainHeader></MainHeader>
    <MainContent></MainContent>
    <SecondContent></SecondContent>
    <MainFooter></MainFooter>
    <FooterOne></FooterOne>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainContent from './components/MainContent.vue'
import SecondContent from './components/SecondContent.vue'
import MainFooter from './components/MainFooter.vue'
import FooterOne from './components/FooterOne.vue'


export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent,
    SecondContent,
    MainFooter,
    FooterOne,
   
},

}
</script>

<style lang="scss">
@import './style/index.scss';
</style>
