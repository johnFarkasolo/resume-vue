<template>
  <div id="app">
		<div class="row">
			<div class="col-12"><Intro></Intro></div>
		</div>
		<div class="row">
			<div class="col-12"><Main></Main>
			</div>
		</div>	
			<div class="row">
					<div class="col-12"><Footer></Footer></div>
			</div>
    <router-view/>
  </div>
</template>

<script>
  import Intro from './components/intro';
  import Footer from './components/footer';
	import Main from './components/main';
	import Parallax from 'vue-parallaxy'
	export default {
		name: 'App',
		components: {Intro, Main, Footer, Parallax}
	}

</script>

<style>
body {
	margin: 0;
	padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
	padding: 0;
}
</style>
