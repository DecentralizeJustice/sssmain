<template>
  <div>
      <v-flex xs12 class="grad hidden-sm-and-down" style="height:80vh;width:100vw;">

          <img src='https://res.cloudinary.com/dylevfpbl/image/upload/v1556067349/plastic/undraw_mind_map_cwng.svg'
          style="height:50%;width:auto;margin-top:5%;">
          <div class="text mt-3">Plastic creates storage that is easy to create and durable. These features make it perfect for
          a distributed system to store your crypto. </div>
        <div class="mt-3">
          <v-btn large color="black">Buy</v-btn>
        </div>

      </v-flex>
      <v-flex xs12 class="hidden-md-and-up grad">
          <img src='https://res.cloudinary.com/dylevfpbl/image/upload/v1556067349/plastic/undraw_mind_map_cwng.svg'
          style="width:75vw;height:auto;margin-top:5%;">
          <div class="textm">Plastic creates storage that is easy to create and durable. These features make it perfect for
          a distributed system to store your crypto.  </div>
          <div class="mt-3 pb-3" >
            <v-btn large color="black" st>Buy</v-btn>
          </div>

    </v-flex>
  </div>
</template>

<script>
export default {
  name: 'sum',
  components: {

  }
}
</script>
<style scoped>
.grad{
  background-image: linear-gradient(to top, #0c3483 0%, #a2b6df 100%, #6b8cce 100%, #a2b6df 100%);
}
.text{
  width:70%;
  margin-left:15%;
  font-size: 4vh;
}
.titlem{
  font-size: 4em
}
.textm{
  font-size: 1.5em;
  width:90%;
  margin-left: 5%;
  margin-top:2.5%;
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
