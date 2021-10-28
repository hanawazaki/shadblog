<template>
  <div class="socmed">
    <div class="title">
      <h3>Follow Me</h3>
    </div>
    <div class="content d-flex justify-content-center">
      <a href="http://facebook.com" target="_blank">
        <img src="../assets/img/fb-md.png" alt="" />
      </a>
      <a href="http://instagram.com" target="_blank">
        <img src="../assets/img/ig-md.png" alt="" />
      </a>
      <a href="http://youtube.com" target="_blank">
        <img src="../assets/img/yt-md.png" alt="" />
      </a>
      <a href="http://twitter.com" target="_blank">
        <img src="../assets/img/twt-md.png" alt="" />
      </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass">
@import "@/css/_variables.sass"
aside
  .socmed
    @include card-sidebar
    .content
      padding: 30px 20px
      img
        width: 50px
        margin: 0 10px
</style>