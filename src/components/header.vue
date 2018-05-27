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
	height: 100vh;
	width: 100%;
	background-image: url('../assets/canvas.png');
	background-size: cover;
	animation: animatedBackground 3s linear infinite;
	-moz-animation: animatedBackground 3s linear infinite;
	-webkit-animation: animatedBackground 3s linear infinite;
 	-o-animation: animatedBackground 3s linear infinite;
}

@-webkit-keyframes AnimationName {
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}
@-moz-keyframes AnimationName {
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}
@keyframes AnimationName {
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}

</style>
