<template>
  <v-container  text-xs-center fluid ma-0 pa-0 >
    <v-layout row wrap ma-0 pa-0 >
      <v-flex xs12 class="back-image">
        <div class="center">
        <div class="display-3">Secure Your Daily Funds</div>
        <div class="display-1">A utility app that helps you manage your daily use keys so that you don't loose them. </div>
      </div>
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
      rgba(13, 152, 186, 0.7),
      rgba(13, 152, 186, 0.7)
    ),
    no-repeat center center fixed
    url(https://res.cloudinary.com/dylevfpbl/image/upload/v1555014467/decentralkeystorage/phone.jpg);
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     height:100vh;width:100vw;
}

.center {
  margin: 0;
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
}

</style>
