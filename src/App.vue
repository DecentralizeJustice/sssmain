<template>
  <v-app dark>
   <!-- <v-toolbar class="white">
     <v-toolbar-title v-text="title"></v-toolbar-title>
   </v-toolbar> -->
   <v-content>
     <section>
       <v-parallax src="https://images.pexels.com/photos/1055336/pexels-photo-1055336.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" height="600">
         <v-layout
           column
           align-center
           justify-center
           class="white--text"
         >
           <img src="./assets/Multisig-Crypto.png" alt="" height="400">
           <h2 class="white--text mb-2 display-1 text-xs-center">Secure Crypto for the Masses</h2>
         </v-layout>
       </v-parallax>
     </section>

     <section>
       <v-layout
         column
         wrap
         class="my-5"
         align-center
       >
         <v-flex xs12 sm4 class="my-3">
           <div class="text-xs-center">
             <h2 class="headline">This project is under development. Here are our main categories of work: </h2>
           </div>
         </v-flex>
         <v-flex xs12>
           <v-container grid-list-xl>
             <v-layout row wrap align-center>
               <v-flex xs12 md6>
                 <v-card >
                    <v-img
                      src="https://images.pexels.com/photos/196644/pexels-photo-196644.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Design Specification</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.google.com">Study</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md6>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/607812/pexels-photo-607812.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Mobile App</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://github.com/DecentralizeJustice/MultisigMobile">Github</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md6>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/374074/pexels-photo-374074.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Desktop App</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://github.com/DecentralizeJustice/MultisigCryptoDesktop">Github</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md6>
                 <v-card>
                    <v-img
                      src="https://userstyles.org/style_screenshots/129171_after.png"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Reddit</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.reddit.com/r/DecentralizeJustice">Ask A Quesion</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
             </v-layout>
           </v-container>
         </v-flex>
       </v-layout>
     </section>

   </v-content>
 </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>
