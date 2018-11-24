<template>
  <div>

  </div>
</template>
<!-- 855343e9656c6bc5524511618732356e2653a187-->
<script>
  export default {
    async mounted() {
      console.log(
        JSON.stringify(await
          this.$axios.$get('https://qiita.com/api/v2/items?query=tag:nuxt.js'), true,  ' ')
      )
    }
  }
</script>