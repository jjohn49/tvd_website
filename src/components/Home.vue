<template>
  <div class="header">
      <img src="../assets/tvd_logo.png">
  </div>
</template>

<script>
export default {
  name: 'Home-view',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img{
    max-height: auto;
    width: 25%;
  }
</style>
