<template>
  <v-parallax src="./assets/img/one-section.jpg">
    <v-layout column align-center justify-center>
      <h1 class="white--text">Vuetify.js</h1>
      <h4 class="white--text">Build your application today!</h4>
    </v-layout>
  </v-parallax>
</template>

<script>
  export default {
    name: 'it Intro',
  }
</script>

<style lang="scss" scoped>

	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box; 
	}
  .intro-body {
    height: 95vh;
		width: 100%;	
	}
	.parallax__content {
		padding: 0;
	}
	parallax__image {
		opacity: 1;
	}

</style>
