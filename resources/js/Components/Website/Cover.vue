<template>
	<div class="w-10/12 md:w-8/12 mx-auto flex items-start md:items-center">
		<div class="w-2/3 pr-4 md:pr-24 relative z-10">
			<h1 class="text-2xl md:text-6xl text-primary mb-4 md:mb-10">
				Las mejores herramientas para un emprendimiento exitoso.
			</h1>
			<p class="text-regular leading-relaxed mb-4 md:mb-10 text-xs md:text-lg"> 
				¡Que nada te impida emprender! Nosotros te ayudamos a que logres tus objetivos construyendo tu página web para potencializar tu negocio a gran velocidad.
			</p>
			<a href="#" class="text-xs md:text-base font-bold text-primary flex items-center">
				<i class="fa fa-envelope mr-3"></i>
				<span class="underline">info@codelandstudio.com</span>
			</a>
		</div>
		<div class="w-1/3 relative">
			<div class="bgImgSquare bg-muted z-1"></div>
			<div class="relative shadow-xl">
				<img src="/img/Codeland_Studio_Foto_2.JPG" class="relative z-5 coverImg wow animate__fadeInUp" alt="">
				<img src="/img/Logo_Codeland_Studio_Icon.svg" class="rounded-full coverIcon absolute bottom-4 left-4 z-1" alt="">
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
	.coverImg{
		width: 100%;
		height: auto;
	}
	.coverIcon{
		width: 75px;
		height: 75px;
	}
	@media screen and (max-width: 640px){
		.bgImgSquare{
			position: absolute;
			bottom: -31px;
			right: 2px;
			width: 225px;
			height: 150px;
		}
		.coverImg{
			max-width: 45vw;
			width: 45vw;
			height: auto
		}
		.coverIcon{
			width: 40px;
			height: 40px;
		}
	}
</style>