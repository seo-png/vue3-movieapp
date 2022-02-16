<template>
  <h1>Movie!</h1>
</template>

<script>
export default {
  created() {
    this.$store.dispatch('movie/searchMovieWithId', {
      //movie/tt123762
      id: this.$route.params.id
    })
  }
}
</script>