<template>
  <Header />
  <Navbar />
  <router-view />
</template>
<script>
import Header from "@/components/Header";
import Navbar from "@/components/Navbar";

export default {
  components: { Header, Navbar },
  setup() {},
};
</script>
<style lang="sass">
@import "@/css/_variables.sass"

#app
  margin: 0 150px
  text-align: center
  font-family: 'Nunito', sans-serif
  font-size: 18px
  font-weight: 300
</style>
