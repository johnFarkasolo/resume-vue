<template>
  <div id="app">
    <Header></Header>
    <Footer></Footer>
    <router-view/>
  </div>
</template>

<script>
  import Header from './components/header';
  import Footer from './components/footer';
export default {
  name: 'App',
  components: {Header, Footer}
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
