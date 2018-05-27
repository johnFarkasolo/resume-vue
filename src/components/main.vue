<template>
	<div class="main-body">
			<parallax>
				<div id="skills">
					
				</div>
			</parallax>
			<parallax>
    		<div id="projects">
						
				</div>
			</parallax>
			<parallax>
    		<div id="contacts">
						
				</div>
			</parallax>
	</div>		
</template>

<script>
  export default {
    name: "main"
	}
</script>

<style scoped>
	#skills {
		height: 100vh;
		width: 100%;
		background: linear-gradient(240deg, #f5925d, #361c83);
	}

	#projects {
		height: 100vh;
		width: 100%;
		background: linear-gradient(230deg, #78139e, #2f0ba8);
	}
	#contacts {
		height: 100vh;
		width: 100%;
		background: linear-gradient(240deg, #5cddd9, #ee4bff);
	}
</style>
