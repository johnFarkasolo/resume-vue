<template>
				<parallax>
					<div class="intro-body">
						<a href="" class="intro-logo"><img src="../assets/logo.png" alt=""></a>
					</div>
				</parallax>
</template>

<script>
    export default {
        name: 'it Intro',
    }
</script>

<style scoped>
.intro-body{
	height: 100vh;
	width: 100%;
	background: linear-gradient(180deg, #bc00ff, #4c0fcc);
	background-size: 300% 300%;
	animation: introGradient 8s ease infinite;
		-webkit-animation: introGradient 8s ease infinite;
		-moz-animation: introGradient 8s ease infinite;
}

@keyframes introGradient {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
.intro-logo {
		margin-top: 50px;
		position: fixed;	
		box-sizing: border-box;
		z-index: 999;
	}
	.intro-logo img{
		width: 50px;
		background: transparent;
	}
</style>
