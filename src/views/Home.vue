<template>
  <div class="home">
    <main class="main">
      <div class="featured">
        <img src="../assets/img/featured-img.png" alt="" />
      </div>
      <div class="blogposts">
        <div class="blog"></div>
      </div>
    </main>

    <aside class="sidebar">sidebar</aside>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "Home",
  components: {},
};
</script>

<style lang="sass">
@import "@/css/_variables.sass"

.home
  margin: 0 150px
  display: grid
  grid-template-areas: "main sidebar" "main sidebar"
  grid-template-columns: 2fr 1fr
  grid-template-rows: 1fr 1fr
  grid-gap: 30px
main
  grid-area: main
  display: grid
  grid-template-areas: "featured " "blogposts"
  grid-template-rows: 1fr 1.5fr
  grid-gap: 30px

  .featured
    grid-area: featured
    height: 342px
    border-radius: 10px
    border: 1px solid $gray
    img
      width: 600px
  .blogposts
    border: 1px solid $gray
    grid-area: blogposts
    border-radius: 10px
    .blog

aside
  border: 1px solid $gray
  grid-area: sidebar
</style>
