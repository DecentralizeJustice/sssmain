<template>
  <v-container  text-xs-center fluid ma-0 pa-0 >
    <v-layout row wrap ma-0 pa-0 >
      <v-flex xs12 class="back-image">
        <div class="title font-weight-light">Secure Your Daily Funds</div>
        <div class="title font-weight-light">A Utility App That </div>
      </v-flex>
      </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'home',
  components: {

  }
}
</script>
<style scoped>
.back-image {
  background:
    /* top, transparent red, faked with gradient */
    linear-gradient(
      rgba(211, 211, 211, 0.7),
      rgba(211, 211, 211, 0.7)
    ),
    no-repeat center center fixed
    url(https://res.cloudinary.com/dylevfpbl/image/upload/v1555014467/decentralkeystorage/phone.jpg);
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     height:100vh;width:100vw;
}

</style>
