<template>
	<div v-if="loading" class="bg-light h-screen w-screen fixed z-50 top-0 left-0 bottom-0 right-0 flex items-center justify-center">
		<div>
			<img src="/img/Logo_Codeland_Studio_Icon.svg" class="h-20 w-auto rounded-full" alt="">
		</div>
	</div>
</template>
<script>
export default {
  name: 'Loader',
  props: {
  	loading: {
  		default: true
  	}
  },
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
</style>