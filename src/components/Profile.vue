<template>
  <div class="profile">
    <div class="title">
      <h3>Selamat Datang!</h3>
    </div>
    <div class="bio">
      <img src="../assets/img/pp.png" alt="" />
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ligula
        eros, tempor nec sem ac, efficitur dapibus augue.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass" >
@import "@/css/_variables.sass"
aside
  .profile
    @include card-sidebar
    .bio
      margin-top: 20px
      padding: 10px 30px
      img
        border-radius: 50px
        width: 170px
      p
        margin-top: 20px
        font-family: $font1
        font-size: 14px
        font-weight: 400
        color: $blue
</style>