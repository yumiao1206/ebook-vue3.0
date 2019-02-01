<template>
  <div class="home">
    <span class="icon-book2"></span>
    <p class="text">abcdefg</p>
  </div>
</template>

<script>
import Epub from 'epubjs'
global.ePub = Epub

export default {
  name: 'home'
}
</script>

<style lang="scss" scoped>
  .text{
    /*font-family: "Days One";*/
    font-size: 1rem;
    color: red;
  }
</style>
