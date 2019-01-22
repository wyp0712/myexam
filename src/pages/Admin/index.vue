<template>
  <div class="home">
    <div class="header">
        page admin
    </div>
    <div class="main">

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
// import HeaderBar from '@/pages/HeaderBar'
import FooterBar from '@/pages/FooterBar'

export default {
  name: 'Admin',
  components: {
    // HelloWorld,
    // HeaderBar,
    FooterBar
  }
}
</script>
