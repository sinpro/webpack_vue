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
	},
}	
</script>
<style lang="scss" scoped>
	
</style>
