<template>
	<header>
	  <div class="container clear">
	  	<div class="logo">
	  		<img :src="logoIcon" />
	  	</div>
	  	<div class="nav">
	  		<img :src="menuIcon" @click="showSidepanel = !showSidepanel" />
	  	</div>

	  	<md-drawer :md-right="true" class="side-drawer" :md-active.sync="showSidepanel"></md-drawer>

	  </div>
	</header>
</template>

<script>
	import Logo from '../../assets/logo.png';
	import Menu from '../../assets/images/menu.png';

	export default {
		data(){
			return {
				logoIcon: Logo,
				menuIcon: Menu,
				showSidepanel: false,
			}
		}
	}
</script>