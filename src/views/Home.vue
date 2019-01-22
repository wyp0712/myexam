<template>
  <div class="home">
    <div class="header">
      <HeaderBar/>
    </div>
    <div class="main">
      <Swiper />
    </div>
    <div class="footer">
      <FooterBar></FooterBar>
    </div>
  </div>
</template>

<script>
import './index.scss'
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderBar from '@/pages/HeaderBar'
import FooterBar from '@/pages/FooterBar'
import Swiper from '@/components/Swiper.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld,
    HeaderBar,
    FooterBar,
    Swiper
  }
}
</script>
