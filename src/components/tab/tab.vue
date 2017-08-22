<template>
  <div class="nav">
    <router-link to="/recommend" tag="div" class="nav-item">推荐</router-link>
    <router-link to="/singer" tag="div" class="nav-item">歌手</router-link>
    <router-link to="/rank" tag="div" class="nav-item">排行</router-link>
    <router-link to="/search" tag="div" class="nav-item">搜索</router-link>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="stylus">
.nav
  height: 35px
  line-height: 35px
  text-align: center
  .nav-item
    display: inline-block
    padding: 0 20px
    color: #999
    &.router-link-active
      color: #f14c4c
      border-bottom: 3px solid #f14c4c




</style>
