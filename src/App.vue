<template>
	<div id="app">
	<router-view></router-view>
	<footer-guide v-show="$route.meta.showFooter"></footer-guide>
	
	</div>
</template>

<script>
 import FooterGuide from './components/FooterGuide/FooterGuide.vue'

 
 export default{
	 components:{
		 FooterGuide,
	 }
	
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
.aap{
	width:100%
	heigth:100%
	background:#f5f5f5
}	
</style>
