<script>
export default {
    name: 'SingleProject',
}
</script>

<template>
    <div class="container">
        <h1>Project name</h1>
        <!-- sintassi per leggere lo slug della pagina -->
        <div>Per leggere slug della pagina slug: {{ $route.params.slug }}</div>  
    </div>

</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>