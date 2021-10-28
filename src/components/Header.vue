<template>
  <div class="header">
    <div class="logo-header">
      <a href="http://facebook.com" target="_blank">
        <img src="../assets/img/fb.png" alt="" />
      </a>
      <a href="http://instagram.com" target="_blank">
        <img src="../assets/img/ig.png" alt="" />
      </a>
      <a href="http://youtube.com" target="_blank">
        <img src="../assets/img/yt.png" alt="" />
      </a>
    </div>
    <div class="title">
      <h1><span>Shadrina Ainin</span></h1>
      <p>Beauty and Lifestyle Blog</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass" scoped>
@import "@/css/_variables.sass"

.header
  margin-top: 20px
  .logo-header
    margin-bottom: 20px
    img
      margin: 0 7px
      width: 20px
  .title
    font-family: 'Nunito'
    h1
      font-size: 45px
      font-weight: 600
      margin-bottom: 3px
      color: $blue
      span
        padding-bottom: 3px
        border-bottom: 1px solid $blue
        line-height: 48px
    p
      font-size: 16px
      font-weight: 300
      margin-top: 10px
      color: $blue
      font-family: $font2
</style>