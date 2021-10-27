<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/categories">Categories</router-link>
    <router-link to="/allpost">All Post</router-link>
    <router-link to="/about">About</router-link>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass">
@import "@/css/_variables.sass"

#nav
  margin-top: 28px
  margin-bottom: 80px
  padding: 20px
  font-size: 16px
  font-weight: 400

  a
    font-weight: bold
    color: $blue
    text-decoration: none
    margin: 0 10px

    &.router-link-exact-active
      background: transparent
      border-radius: 10px
      height: 5px
      box-shadow: 0 40px 0 0 $pink
      display: inline-block
</style>