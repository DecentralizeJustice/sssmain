<template>
  <div>
      <v-flex xs12 class="back-image hidden-sm-and-down" style="height:80vh;">
        <div class="center">
        <div class="main">SSS Backup</div>
        <div class="display-1 mt-3">A felxible and easy method to backup your crypto.</div>
        <div class="mt-3">
          <v-btn large color="black">Start</v-btn>
        </div>
      </div>
      </v-flex>
      <v-flex xs12 class="hidden-md-and-up grad">
        <v-flex xs12 class="" style=''>
          <img src="https://res.cloudinary.com/dylevfpbl/image/upload/v1556168910/sss/access-background-black-761149.jpg"
          style="height:auto;width:100vw;">
        </v-flex>
        <v-flex sx12 style="padding-bottom:4vh;">
          <div class="">
            <div class="titlem">SSS Backup</div>
            <div class="textm mt-3">A felxible and easy method to backup your crypto.</div>
            <div class="mt-3">
              <v-btn large color="black">Try</v-btn>
            </div>
          </div>
      </v-flex>
    </v-flex>
  </div>
</template>

<script>
export default {
  name: 'hero',
  components: {

  }
}
</script>
<style scoped>
.grad{
  background-image: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
}
.back-image {
  background:
    no-repeat center center fixed
    url(https://res.cloudinary.com/dylevfpbl/image/upload/v1556168910/sss/access-background-black-761149.jpg);
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     height:100vh;width:100vw;
}
.titlem{
  font-size: 4em
}
.textm{
  font-size: 1.8em
}
.center {
  margin: 0;
  position: relative;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgb(169,169,169,.9);
  border-radius: 5vw;
  padding: 1%;
  width:50vw;
}
.main{
  font-family: 'Helvetica', sans-serif;
  font-size: 13vh;
}

</style>
