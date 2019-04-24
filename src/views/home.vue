<template>
  <v-container  text-xs-center fluid ma-0 pa-0 >
    <v-layout row wrap ma-0 pa-0 >
      <hero/>
      <videod class="hidden-sm-and-down"/>
      <sum/>
      <feat class='grad'/>
      </v-layout>
  </v-container>
</template>

<script>
import hero from '@/components/hero.vue'
import videod from '@/components/video.vue'
import sum from '@/components/sum.vue'
import feat from '@/components/feat.vue'
export default {
  name: 'home',
  components: {
    hero,
    videod,
    sum,
    feat
  }
}
</script>
<style scoped>

.main{
  font-family: 'Helvetica', sans-serif;
  font-size: 14vh;
}
.grad{
  background-image: linear-gradient(-20deg, #6e45e2 0%, #88d3ce 100%);
}

</style>
