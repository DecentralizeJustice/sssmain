<template>
  <v-container  text-xs-center fluid ma-0 pa-0 >
    <v-layout row wrap ma-0 pa-0 >
      <hero/>
      <videod class="hidden-sm-and-down"/>
      </v-layout>
  </v-container>
</template>

<script>
import hero from '@/components/hero.vue'
import videod from '@/components/video.vue'
export default {
  name: 'home',
  components: {
    hero,
    videod
  }
}
</script>
<style scoped>

.main{
  font-family: 'Helvetica', sans-serif;
  font-size: 14vh;
}

</style>
