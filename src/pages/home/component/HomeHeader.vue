<template>
  <div class="header">
    <div class="header-title"></div>
    <div class="header-serch">
      11111
    </div>
    <div  to="/" class="header-app border-right" >下载APP</div>
    <div class="header-more">更多</div>
  </div>
</template>
<script>
export default {
  name:'HomeHeader'
}
</script>
<style lang="stylus" scoped>
// 1rem = html font-size =50px
.header
  display flex
  width 100%
  height .86rem
  background red
  padding .1rem
  .header-title
    float left
    background-image  url(https://www.zhihu.com/app/5b92a3323be75dfa0fd99749ac7182a5.svg)
    background-size: cover;
    display: inline-block;
    height: .42rem
    vertical-align: top;
    width: .9rem
  .header-serch
    flex 1
    background hsla(0,0%,92.2%,.72)
    border-radius .2rem
  .header-app
    flex 1
    float  left 
    width .84rem
    color: #0084ff
  .header-more
    flex 1
</style>