<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">Rookies Music</h1>
  </div>
</template>

<script type="text/ecmascript-6">
export default {

}
</script>

<style lang="stylus" scoped>
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"

  .m-header
    position relative
    height 44px
    text-align center
    color $color-theme
    font-size 0
    .icon
      display inline-block
      vertical-align top
      bg-image('logo')
      width 30px
      height 32px
      background-size 30px 32px
      margin-top 6px
      margin-right 9px
    .text
      vertical-align top
      display inline-block
      line-height 44px
      font-size $font-size-large
</style>
