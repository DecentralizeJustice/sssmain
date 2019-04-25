<template>
  <v-layout row wrap ma-0 pa-0 align-center justify-space-around>

      <featcard v-for="item in data" :key="item.title" v-bind:item='item' />

  </v-layout>
</template>

<script>
import featcard from '@/components/featcard.vue'
export default {
  name: 'feat',
  components: {
    featcard
  },
  data () {
    return {
      data: [
        {
          img: 'https://res.cloudinary.com/dylevfpbl/image/upload/v1555918573/keysbyanymeans/undraw_marketing_v0iu_1.svg',
          title: 'Custom',
          text: `You can use this app to store your crypto anyway that works best for you. `,
          link: 'https://www.google.com'
        },
        {
          img: 'https://res.cloudinary.com/dylevfpbl/image/upload/v1556071118/plastic/undraw_voice_interface_eckp.svg',
          title: 'Easy',
          text: `This method is powerful yet easy to use to store your crypto.`,
          link: 'https://www.google.com'
        },
        {
          img: 'https://res.cloudinary.com/dylevfpbl/image/upload/v1556071038/plastic/undraw_vault_9cmw.svg',
          title: 'Redundant',
          text: `This system allows you to build a redudant system that is safe from all forms of disasters.`,
          link: 'https://www.google.com'
        }
      ]

    }
  }
}
</script>
<style scoped>
.buttonOpt {
  color:  white;
  font-size: 1.4rem;
}
.fullheight{
  height:100%;
}
.titlet{
font-size: 500%;
font-weight: bold;
}
.titlem{
font-size: 300%;
font-weight: bold;
}

</style>
