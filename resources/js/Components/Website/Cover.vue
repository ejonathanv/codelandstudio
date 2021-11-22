<template>
	<div class="w-8/12 mx-auto flex items-center">
		<div class="w-2/3 pr-24 relative z-10">
			<h1 class="text-6xl text-primary mb-10">
				Las mejores herramientas para un emprendimiento exitoso.
			</h1>
			<p class="text-regular leading-relaxed mb-10 text-lg"> 
				¡Que nada te impida emprender! Nosotros te ayudamos a que logres tus objetivos construyendo tu página web para potencializar tu negocio a gran velocidad.
			</p>
			<a href="#" class="font-bold text-primary flex items-center">
				<i class="fa fa-envelope mr-3"></i>
				<span class="underline">info@codelandstudio.com</span>
			</a>
		</div>
		<div class="w-1/3 relative">
			<div class="bgImgSquare bg-muted z-1"></div>
			<div class="relative shadow-xl">
				<img src="/img/Codeland_Studio_Foto_2.JPG" class="w-full relative z-5 wow animate__fadeInUp" alt="">
				<img src="/img/Logo_Codeland_Studio_Icon.svg" class="h-20 w-20 rounded-full absolute bottom-4 left-4 z-1" alt="">
			</div>
		</div>
	</div>
</template>
<script>
export default {
  name: 'Cover',
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
	.bgImgSquare{
		position: absolute;
		bottom:30px;
		right: 80px;
		width: 620px;
		height: 300px;
	}
</style>