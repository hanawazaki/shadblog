<template>
  <div class="home">
    <main class="main">
      <Featured />
      <div class="blogposts">
        <div class="blog"></div>
      </div>
    </main>
    <aside class="sidebar">
      <Profile />
      <Socmed />
      <PopularPost />
      <Tags />
    </aside>
    <Footer />
  </div>
</template>

<script>
import Featured from "@/components/Featured";
import Profile from "@/components/Profile";
import Socmed from "@/components/Socmed";
import PopularPost from "@/components/PopularPost";
import Tags from "@/components/Tags";
import Footer from "@/components/Footer";

export default {
  name: "Home",
  components: { Featured, Profile, Socmed, PopularPost, Tags, Footer },
};
</script>

<style lang="sass" scoped>
@import "@/css/_variables.sass"

.home
  display: grid
  grid-template-areas: "main sidebar" "main sidebar"
  grid-template-columns: 2fr 1fr
  grid-template-rows: 1fr 1fr
  grid-gap: 25px
  main
    grid-area: main
    display: grid
    grid-template-areas: "featured " "blogposts"
    grid-template-rows: 1fr 2fr
    grid-gap: 25px

    .blogposts
      border: 1px solid $gray
      grid-area: blogposts
      border-radius: 10px

  aside
    grid-area: sidebar
  footer
    grid-area: footer
    grid-column: span 2
</style>
