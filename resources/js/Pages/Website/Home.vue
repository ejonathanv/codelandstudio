<template>
  <div>
    <Cover />
    <Web-Development-Section />
    <Graphic-Design-Section />
    <Photography-Section />
    <Instagram-Feed />
  </div>
</template>
<script>
import GuestLayout from '@/Layouts/Guest';
import Cover from '@/Components/Website/Cover';
import WebDevelopmentSection from '@/Components/Website/WebDevelopmentSection';
import GraphicDesignSection from '@/Components/Website/GraphicDesignSection';
import PhotographySection from '@/Components/Website/PhotographySection';
import InstagramFeed from '@/Components/Website/InstagramFeed';
export default {
  name: 'Home',
  layout: GuestLayout,
  components: {Cover, WebDevelopmentSection, GraphicDesignSection, PhotographySection, InstagramFeed},
  data () {
    return {
    }
  }
}
</script>
<style lang="css" scoped>
</style>