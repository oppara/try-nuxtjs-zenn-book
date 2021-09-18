<template>
  <div >
    <div class="editor">
      <img src="images/editor.jpg" alt="">
    </div>
    <div class="jumbotron">
      <h1 class="display-4">Hello, world!</h1>
      <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
      <hr class="my-4">
      <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
      <nuxt-link class="btn btn-primary btn-lg" to="/contact">お問い合わせ</nuxt-link>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.editor {
  text-align: center;
}
.editor img {
  width: 40%;
}

</style>
