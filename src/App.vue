<script>
  import ProjectsList from './components/ProjectsList.vue';
  
  export default {
    components: {
      ProjectsList,
    }
  }
</script>

<template>
  <h1>Ciao ciao</h1>
  <ProjectsList></ProjectsList>
</template>

<style lang="scss">
@use './style/generic';
@use './style/partials/variables' as *;  // le variables vanno importate in tutti ii componenti figli se vengono usate

h1 {
  color: $main-color;
}

</style>