<template>
  <div>{{ movie.imdbID }}</div>
</template>

<script>
export default {
  props: {
    movie: {
      type: Object,
      default: () => ({})
      //일반 함수 default: function () {return {}}
    }
  }
}
</script>