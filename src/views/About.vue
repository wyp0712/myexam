<template>
  <div class="home">
    <div class="header">
      <!-- <HeaderBar/> -->
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
import FooterBar from '@/pages/FooterBar'

export default {
  name: 'About',
  components: {
    FooterBar
  }
}
</script>
