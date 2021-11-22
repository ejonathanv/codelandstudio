<template>
	<section class="pt-24 pb-60">
		<div class="w-8/12 mx-auto flex items-center space-x-24">
			<div class="w-1/2 relative">
				<h3 class="text-6xl mb-10 text-primary">Fotografía</h3>
				<p class="text-lg text-opacity-75 mb-10 text-primary">
					Sabemos lo importante que es realizar campañas constantes para alcanzar a tu audiencia y lo tedioso que puede ser el tener que diseñar tus publicaciones y mantener congruencia entre estas.
				</p>
				<a href="#" class="text-primary font-bold underline hover:text-opacity-75">
					Continuar leyendo
				</a>
			</div>
			<div class="w-1/2 relative wow animate__fadeInUp">
				<img src="/img/Codeland_Studio_Foto_3.jpg" class="w-full h-auto absolute z-1 imgBefore shadow-xl" alt="">
				<img src="/img/Codeland_Studio_Foto_5.jpg" class="w-full h-auto relative z-5 shadow-xl" alt="">
			</div>
		</div>
	</section>
</template>
<script>
export default {
  name: 'PhotographySection',
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
.imgBefore{
  top: 50%;
  right: 15%;
}
</style>