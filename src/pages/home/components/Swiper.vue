<template>
<div class="wrapper">
  <swiper :options="swiperOption">
    <swiper-slide v-for='item of swiperList' :key='item.id'>
      <img class='swiper-img' :src="item.imgUrl" />
    </swiper-slide>
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</div>
</template>
<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [{
        id: '0001',
        imgUrl: 'https://aecpm.alicdn.com/simba/img/TB1CWf9KpXXXXbuXpXXSutbFXXX.jpg_q50.jpg'
      }, {
        id: '0002',
        imgUrl: '//gw.alicdn.com/imgextra/i3/76/TB23tKuIbSYBuNjSspfXXcZCpXa_!!76-0-lubanu.jpg'
      }]
    }
  }
}
</script>
<style lang="stylus" scoped>
  .wrapper >>> .swiper-pagination-bullet-active
    background: #fff
  .wrapper
    overflow: hidden
    width: 100%
    height: 0
    padding-bottom: 31.25%
    .swiper-img
      width: 100%
</style>
