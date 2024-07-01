<script>
export default {
  name: 'ProjectsList'

}
</script>

<template>
  <div class="container">
    <h1>All projects</h1>

    <!-- Single project template -->
    <div class="row row-cols-3">
      <div class="col">
        <div class="card">
          <img src="..." class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
    <!-- / Single project template -->
  </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>