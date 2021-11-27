<template>
	<div>
		<div class="font-bold credits text-xs md:text-base text-primary hidden md:block">
			2021, Codeland Studio, Calidad y Profesionalismo.
		</div>
		<div class="font-bold followLinks text-xs md:text-base text-primary">
			Síguenos en <a href="#" class="underline">Instagram</a> y <a href="#" class="underline">Facebook</a>
		</div>
	</div>
</template>
<script>
export default {
  name: 'FollowLinks',
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
	.credits{
		position: fixed;
		top: 49%;
		left: -134px;
		z-index: 10;
		transform: rotate(-90deg);
	}
	.followLinks{
		position: fixed;
		top: 53%;
		right: -75px;
		z-index: 10;
		transform: rotate(90deg);
	}
</style>