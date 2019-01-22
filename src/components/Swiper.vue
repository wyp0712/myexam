<template>
  <div class='swiper-container'>
    <div class='swiper-wrapper'>
      <div class='swiper-slide' v-for='item in listImg' :key='item.id'>
        <img :src='item.img' alt>
      </div>
      <!-- <div class='swiper-slide'>
         <img src='../assets/imgs/1.jpg' alt=''>
      </div>-->
    </div>
    <!-- 如果需要分页器 -->
    <!-- <div class='swiper-pagination'></div> -->
    <!-- 如果需要导航按钮 -->
    <!-- <div class='swiper-button-prev'></div>
    <div class='swiper-button-next'></div>-->
    <!-- 如果需要滚动条 -->
    <!-- <div class='swiper-scrollbar'></div> -->
  </div>
</template>
<script>
import Swiper from 'swiper';
import 'swiper/dist/css/swiper.min.css';
export default {
  name: 'Swiper',
  data() {
    return {
      listImg: [
        {
          id: 0,
          img: require('../assets/imgs/1.jpg')
        },
        {
          id: 1,
          img: require('../assets/imgs/2.jpg')
        },
        {
          id: 2,
          img: require('../assets/imgs/3.jpg')
        },
        {
          id: 3,
          img: require('../assets/imgs/4.jpg')
        }
      ]
    };
  },
  mounted() {
    // this.nextTick(function() {
      // DOM 更新了
      /* eslint-disable no-new */
      new Swiper('.swiper-container', {});
    // })
  }
}
</script>
<style lang='scss'>
.swiper-container {
  width: 100%;
  height: 200px;
  overflow: hidden;
  border-bottom: 1px solid burlywood;
  .swiper-wrapper {
    width: 100%;
    height: 100%;
    .swiper-slide {
      width: 100%;
      height: 100%;
      img {
        width: 100%;
        height: 100%;
      }
    }
  }
}
</style>
