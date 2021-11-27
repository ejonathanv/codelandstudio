<template>
	<header class="py-12 md:py-20">
		<div class="w-10/12 md:w-8/12 mx-auto flex flex-col md:flex-row items-center md:items-start justify-center md:justify-start space-y-10 md:space-y-0">
			<a href="#" class="block">
				<img src="/img/Logo_Codeland_Studio.svg" class="h-12 w-auto" alt="">
			</a>
			<nav class="mx-auto md:mx-0 md:ml-auto flex flex-col space-y-3 items-center">
				<a href="#" class="underline text-center text-primary font-bold hover:text-opacity-75">¡Adquiere una cotización hoy mismo!</a>
				<div class="flex items-center space-x-4 md:space-x-7 uppercase text-xs">
					<a class="text-primary hover:text-opacity-75" href="#">Inicio</a>
					<a class="text-primary hover:text-opacity-75" href="#">Servicios</a>
					<a class="text-primary hover:text-opacity-75" href="#">Precios</a>
					<a class="text-primary hover:text-opacity-75" href="#">Contacto</a>
				</div>
			</nav>
		</div>
	</header>
</template>
<script>
export default {
  name: 'Header',
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
</style>