<template>
  <div class="featured">
    <div class="content">
      <a class="pill">Lifestyle</a>
      <a class="pill">Olahraga</a>
      <h1 class="">Tips mengecilkan perut dengan olahraga kardio</h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass">
@import "@/css/_variables.sass"
.home
  .featured
    grid-area: featured
    height: 400px
    border-radius: 10px
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.5) 97.4%), url("../assets/img/featured-img.png")
    background-position: center
    background-repeat: no-repeat
    background-size: cover
    position: relative
    @include card-shadow
    .content
      text-align: left
      position: absolute
      top: 70%
      left: 40%
      transform: translate(-45%, -45%)
      color: white
      font-family: 'Open sans'
      font-size: 45px
      font-weight:
      width: 500px
      .pill
        border-radius: 20px
        background-color: $pink
        color: white
        font-size: 12px
        padding: 5px 10px
        text-decoration: none
        font-family: $font2
        font-weight: bold
        margin: 0 5px
</style>