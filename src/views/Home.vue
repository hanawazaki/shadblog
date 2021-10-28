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
      <!-- <OtherPost /> -->
    </aside>
  </div>
</template>

<script>
import Featured from "@/components/Featured";
import Profile from "@/components/Profile";
import Socmed from "@/components/Socmed";
import PopularPost from "@/components/PopularPost";
import Tags from "@/components/Tags";
import OtherPost from "@/components/OtherPost";

export default {
  name: "Home",
  components: { Featured, Profile, Socmed, PopularPost, Tags, OtherPost },
};
</script>

<style lang="sass" scoped>
@import "@/css/_variables.sass"

.home
  display: grid
  grid-template-areas: "main sidebar" "main sidebar"
  grid-template-columns: 2fr 1fr
  grid-template-rows: 1fr 1fr
  grid-gap: 30px
  main
    grid-area: main
    display: grid
    grid-template-areas: "featured " "blogposts" "blogposts"
    grid-template-rows: 1fr 2fr
    grid-gap: 30px

    .blogposts
      border: 1px solid $gray
      grid-area: blogposts
      border-radius: 10px

  aside
    grid-area: sidebar
</style>
