<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1804/ff/fdf170ee89594b02.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1803/6a/45f595250c73d102.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1803/20/831d62d2e1c7be02.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1803/76/eb88861d78fb9902.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1803/6c/9e54a8540fee0102.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1804/5a/13ceb38dcf262f02.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class='icon-img-content' src="https://imgs.qunarzz.com/piao/fusion/1804/95/8d02011d149bdb02.png" alt="" />
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeIcons'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .icons
    overflow:hidden
    height:0
    padding-bottom:50%
    .icon
      position:relative
      float:left
      width:25%
      padding-bottom:25%
      .icon-img
        position:absolute
        left:0
        top:0
        right:0
        bottom:.44rem
        box-sizing:border-box
        padding:.1rem
        .icon-img-content
          display:block
          margin:0 auto
          height:100%
      .icon-desc
        position:absolute
        left:0
        right:0
        bottom:0
        height:.44rem
        line-height:.44rem
        text-align:center
        color:$darkTextColor
</style>
