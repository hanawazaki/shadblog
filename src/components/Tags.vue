<template>
  <div class="tags">
    <div class="title">
      <h3>Tags</h3>
    </div>
    <div class="content p-3 d-flex flex-wrap justify-content-center">
      <a href="#" class="pill">Olahraga</a>
      <a href="#" class="pill">Masak</a>
      <a href="#" class="pill">Makeup</a>
      <a href="#" class="pill">Skincare</a>
      <a href="#" class="pill">Kesehatan</a>
      <a href="#" class="pill">Olahraga</a>
      <a href="#" class="pill">Masak</a>
      <a href="#" class="pill">Makeup</a>
      <a href="#" class="pill">Skincare</a>
      <a href="#" class="pill">Kesehatan</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="sass">
@import "@/css/_variables.sass"

aside
  .tags
    @include card-sidebar
    .content
      .pill
        @include pill
</style>