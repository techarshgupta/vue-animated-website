<template>
  <footer>
  	<div class="container">
  		<div>
  			<img :src="logoIcon"/>
  			<div class="contact">
  				<div>Call US</div>
  				<div>345678906789</div>
  			</div>
  		</div>
  	</div>
  </footer>
</template>

<script>
	import Logo from '../../assets/logo.png';

	export default {
		data(){
			return {
				logoIcon: Logo,
			}
		}
	}
</script>