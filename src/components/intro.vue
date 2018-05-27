<template>
			<div class="intro-body">
				<div class="container">
					<div class="row">
						<div class="col">
							<a class="intro-logo" href="#"><img src="../assets/logo.png" alt=""></a>
							<div class="rotate-shadows"></div>
						</div>
					</div>
				</div>
			</div>
</template>

<script>
    export default {
        name: 'it Intro',
    }
</script>

<style scoped>
.intro-body{
	height: 100vh;
	position: relative;
	display: flex;
	justify-content: center;
	background: linear-gradient(45deg, #bc00ff, #4c0fcc);
	background-size: 300% 300%;
	animation: Gradient 6s ease infinite;
		-webkit-animation: Gradient 6s ease infinite;
		-moz-animation: Gradient 6s ease infinite;
}
	.intro-logo {
		top: 100px;
		position: absolute;	
		box-sizing: border-box;
	}
		.intro-logo img{
			width: 50px;
			background: transparent;
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

.rotate-shadows {
  width: 220px;
  height: 220px;
  position: relative;
}
.rotate-shadows:after,
.rotate-shadows:before {
  content: "";
  border-radius: 50%;
  position: absolute;
  top: 10px;
  left: 470px;
  width: 100%;
  height: 100%;
  transform-origin: center center;
}
.rotate-shadows:before {
  box-shadow: inset 0 20px 0 rgba(0, 250, 250, 0.6), inset 20px 0 0 rgba(0, 200, 200, 0.6), inset 0 -20px 0 rgba(0, 150, 200, 0.6), inset -20px 0 0 rgba(0, 200, 250, 0.6);
  animation: rotate-before 2s -0.5s linear infinite;
}
.rotate-shadows:after {
  box-shadow: inset 0 20px 0 rgba(250, 250, 0, 0.6), inset 20px 0 0 rgba(250, 200, 0, 0.6), inset 0 -20px 0 rgba(250, 150, 0, 0.6), inset -20px 0 0 rgba(250, 100, 0, 0.6);
  animation: rotate-after 2s -0.5s linear infinite;
}
@keyframes rotate-after {
  0% {transform: rotateZ(0deg) scaleX(1) scaleY(1);}
  50% {transform: rotateZ(180deg) scaleX(0.82) scaleY(0.95);}
  100% {transform: rotateZ(360deg) scaleX(1) scaleY(1);}
}
@keyframes rotate-before {
  0% {transform: rotateZ(0deg) scaleX(1) scaleY(1);}
  50% {transform: rotateZ(-180deg) scaleX(0.95) scaleY(0.85);}
  100% {transform: rotateZ(-360deg) scaleX(1) scaleY(1);}
}
</style>
