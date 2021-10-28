<template>
  <div class="other">
    <div class="title">
      <h3>Other Posts</h3>
    </div>
    <div class="content d-flex flex-column">
      <div class="row p-3">
        <div class="col-3">
          <img src="../assets/img/blog-img.png" alt="" />
        </div>
        <div class="col-9">
          <a href="#" class="">
            <h6>
              Cara menghilangkan bekas jerawat hitam, bruntusan, breakout dengan
              cepat dan aman
            </h6>
          </a>
        </div>
      </div>
      <div class="row p-3">
        <div class="col-3">
          <img src="../assets/img/blog-img.png" alt="" />
        </div>
        <div class="col-9">
          <a href="#" class="">
            <h6>
              Cara menghilangkan bekas jerawat hitam, bruntusan, breakout dengan
              cepat dan aman
            </h6>
          </a>
        </div>
      </div>
      <div class="row p-3">
        <div class="col-3">
          <img src="../assets/img/blog-img.png" alt="" />
        </div>
        <div class="col-9">
          <a href="#" class="">
            <h6>
              Cara menghilangkan bekas jerawat hitam, bruntusan, breakout dengan
              cepat dan aman
            </h6>
          </a>
        </div>
      </div>
      <div class="row p-3">
        <div class="col-3">
          <img src="../assets/img/blog-img.png" alt="" />
        </div>
        <div class="col-9">
          <a href="#" class="">
            <h6>
              Cara menghilangkan bekas jerawat hitam, bruntusan, breakout dengan
              cepat dan aman
            </h6>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>


<style lang="sass">
@import "@/css/_variables.sass"
aside
  .other
    @include card-sidebar
    .content
      .row
        img
          width: 70px
        a
          text-decoration: none
          h6
            font-family: $font2
            font-size: 14px
            font-weight: 600
            text-align: left
            color: $blue
</style>