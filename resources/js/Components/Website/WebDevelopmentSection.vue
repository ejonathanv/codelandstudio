<template>
	<section class="mt-10 md:mt-24 py-10 md:py-24 bg-muted">
		<div class="w-full md:w-8/12 mx-auto flex items-center">
      <div class="w-2/3 relative">
        <div class="bgImgSquare bg-muted-dark z-1"></div>
        <img src="/img/Codeland_Studio_Foto_6.jpg" class="relative z-10 webDevelopmentImg shadow-xl wow animate__fadeInUp" alt="">
        <div class="absolute bottom-10 bg-muted p-4 text-base leading-snug md:text-3xl font-bold quote z-20 text-primary">
          Nunca antes fue tan sencillo tener tu página web y en un ¡tiempo record!
        </div>
      </div>
    </div>
    <div class="w-full md:w-8/12 mx-auto flex items-center mt-20">
      <a href="#" class="text-lg md:text-2xl mx-auto font-bold text-primary underline hover:text-opacity-75 text-center">
        ¡Me interesa una página web!
      </a>
    </div>
	</section>
</template>
<script>
export default {
  name: 'WebDevelopmentSection',
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
.bgImgSquare{
  position: absolute;
  background-color: #c8e7e7;
  top: -40px;
  left: 30px;
  width: 620px;
  height: 300px;
}
.quote{
  right: -344px;
  width: 70%;
}
@media screen and (max-width: 640px){
  .bgImgSquare{
    top: -19px;
    left: 19px;
    width: 100%;
    height: 172px;
  }

  .webDevelopmentImg{
    max-width: 80vw;
    width: 80vw;
  }

  .quote{
    right: -76px;
    width: 70%;
    bottom: -58px;
  }
}
</style>