<template>
  <div id="app">
    <MainHeader></MainHeader>
    <BgContent></BgContent>
    <MainContent></MainContent>
    <SecondContent></SecondContent>
    <MainFooter></MainFooter>
    <FooterButton></FooterButton>
   
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainContent from './components/MainContent.vue'
import SecondContent from './components/SecondContent.vue'
import MainFooter from './components/MainFooter.vue'
import FooterButton from './components/FooterButton.vue'
import BgContent from './components/BgContent.vue'



export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent,
    SecondContent,
    MainFooter,
    FooterButton,
    BgContent,
    
   
},

}
</script>

<style lang="scss">
@import './style/index.scss';
</style>
