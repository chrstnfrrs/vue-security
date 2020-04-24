<template>
  <div>
    <NavBar />
    <nuxt />
  </div>
</template>

<script>
import NavBar from '~/components/NavBar'
export default {
  components: {
    NavBar
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
li{
  margin-bottom: 4px;
}
.content{
  padding: 32px;
  background: #181818;
  color: #eee;
  min-height: 100vh;
}
.heading{
  margin-bottom: 16px;
}
.subHeading{
  margin: 12px 0px;
}
.pageLink{
  color: #e5e5e5;
}
</style>
