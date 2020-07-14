<template>
	<div>
		<h1>wpvue1111</h1>
	</div>
</template>
<script>
export default {
	data(){
		return {
			
		}
	},
	mounted(){
		if(process.env.NODE_ENV==='development'){
			window.app=this;
		}
		console.log(process.env.NODE_ENV)
		console.log(ENV_CONFIG)
		console.log(111111111111111)
	},
}	
</script>
<style lang="scss" scoped>
	
</style>
