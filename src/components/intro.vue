<template>
			<div id="backGround"></div>
</template>

<script>
    export default {
        name: 'it Intro',
    }
</script>

<style scoped>
#backGround{
	height: 100vh;
	width: 100%;
	background-image: url('../assets/canvas.png');
	background-size: cover;
	background: linear-gradient(319deg, #bc00ff, #4c0fcc);
	background-size: 400% 400%;

-webkit-animation: AnimationName 5s ease infinite;
-moz-animation: AnimationName 5s ease infinite;
animation: AnimationName 5s ease infinite;
}

 @-webkit-keyframes AnimationName {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
@-moz-keyframes AnimationName {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
@keyframes AnimationName {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
</style>
