<template>
  <parallax>
    <div class="footer-body"></div>
  </parallax>
</template>

<script>
  export default {
    name: "footer"
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';

  .footer-body {
    height: 100vh;
    width: 100%;
    background: linear-gradient(240deg, #03595c, #210b5d);
  }
</style>
