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
          text: `This kit allows you to create whatever system you want to use to back up your crypto. `,
          link: 'https://www.google.com'
        },
        {
          img: 'https://res.cloudinary.com/dylevfpbl/image/upload/v1556071118/plastic/undraw_voice_interface_eckp.svg',
          title: 'Easy',
          text: `This method of storage is much easier than other metal forms of storage.`,
          link: 'https://www.google.com'
        },
        {
          img: 'https://res.cloudinary.com/dylevfpbl/image/upload/v1556071038/plastic/undraw_vault_9cmw.svg',
          title: 'Durable',
          text: `This kit allows you to build a system of crypto storage that does not fail silentlty. It can withstand water and
          other forms of decay.`,
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
