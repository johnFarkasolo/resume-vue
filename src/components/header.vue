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
	/* background-image: url('../assets/canvas.png'); */
	/* background-size: cover; */
	background: linear-gradient(319deg, #bc00ff, #4c0fcc);
	background-size: 400% 400%;

-webkit-animation: Gradient 6s ease infinite;
-moz-animation: Gradient 6s ease infinite;
animation: Gradient 6s ease infinite;
}

 @-webkit-keyframes Gradient {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
@-moz-keyframes Gradient {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
@keyframes Gradient {
    0%{background-position:87% 0%}
    50%{background-position:14% 100%}
    100%{background-position:87% 0%}
}
</style>
