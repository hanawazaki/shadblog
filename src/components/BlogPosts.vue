<template>
  <div class="blogpost">
    <h3>Recent Posts</h3>
    <div class="row">
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img2.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img2.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img2.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="">
          <img
            src="../assets/img/post-img.png"
            class="card-img-top"
            alt="img_blog"
          />
          <div class="card-body">
            <h5 class="date-post">Juni 28, 2021</h5>
            <h5 class="card-title">
              Tips mengecilkan perut dengan olahraga kardio
            </h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              ligula eros, tempor nec sem ac, efficitur dapibus augue.
            </p>
            <a href="#" class="pill">Olahraga</a>
            <a href="#" class="pill">Kesehatan</a>
          </div>
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

.blogpost
  h3
    font-family: $font1
    font-size: 20px
    font-weight: 600
    text-align: left
    color: $blue
.card
  font-family: $font2
  width: 20rem
  border-radius: 10px !important
  text-align: left
  margin-bottom: 30px
  @include card-shadow
  .date-post
    font-size: 14px
    font-weight: 300
  .card-title
    font-family: 'Open sans'
    font-size: 20px
    font-weight: 600
    color: $blue
  .card-body
    font-size: 16px
    font-weight: 400
    color: $gray
    line-height: 22px
  .pill
    @include pill
</style>