<template>
	<div class="m-header">
	    <div class="icon"></div>
	    <h1 class="text">QQ音乐</h1>
	    <router-link class="mine" tag="div" to="/user">
	    	<i class="icon-mine"></i>
	    </router-link>
	</div>
</template>
<script type="text/ecmascript-6">
	export default{}
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
	@import "~common/stylus/variable"
	@import "~common/stylus/mixin"

	.m-header
	  position: relative
	  height: 44px
	  color: $color-text-h
	  font-size: 0
	  background: $color-background-h
	  .icon
	    display: inline-block
	    vartical-align: top
	    width: 30px
	    height: 32px 
	    margin: 6px 5px 0 10px
	    bg-image('logo')
	    background-size: 106px 32px
	  .text
	  	display: inline-block
	  	vertical-align: top
	  	line-height: 44px
	  	font-size: $font-size-large
	  .mine
	  	position: absolute
	  	top: 0
	  	right: 0
	  	.icon-mine
	  		display: block
	  		padding: 12px
	  		font-size: 20px
	  		color: $color-theme-h
</style>