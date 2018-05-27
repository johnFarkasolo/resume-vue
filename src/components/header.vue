<template>
			<div id="backGround"></div>
</template>

<script>
    export default {
        name: 'it Header',
    }
</script>

<style scoped>
#backGround{
	height: 400px;
	width:100%;
	background-image: url('../assets/canvas.png');
	background-size: cover;
	animation: animatedBackground 60s linear infinite;
	-moz-animation: animatedBackground 60s linear infinite;
	-webkit-animation: animatedBackground 60s linear infinite;
 	-o-animation: animatedBackground 60s linear infinite;
}

@keyframes animatedBackground {
    0 {
        background-position: 0 0
    }
    100% {
        background-position: -600px 600px
    }
}


</style>
