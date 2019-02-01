<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {}
document.addEventListener('DOMContentLoaded', () => {
  const html = document.querySelector('html')
  let fontSzie = window.innerWidth / 10
  fontSzie = fontSzie > 50 ? 50 : fontSzie
  html.style.fontSize = fontSzie + 'px'
})
</script>

<style>

</style>
