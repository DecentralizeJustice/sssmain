<template>
  <v-app dark>
   <!-- <v-toolbar class="white">
     <v-toolbar-title v-text="title"></v-toolbar-title>
   </v-toolbar> -->
   <v-container  text-xs-center fluid pa-0>
   <v-content>
     <section>
       <v-parallax src="https://images.pexels.com/photos/1055336/pexels-photo-1055336.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" height="500">
         <v-layout
           column
           align-center
           justify-center
           class="white--text"
         >
          <v-flex xs1 md1>
           <v-img :src="require('./assets/Multisig-Crypto.png')"
           alt="" style="max-width: 100%; width:100%;"/>
           <h2 class="white--text  display-2 text-xs-center">Distributed & Secure Crypto Wallet</h2>
         </v-flex>
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
             <h2 class="headline">Crpto protocols are distributd, your wallet should be also. Here are the parts of our project that work to make that happen: </h2>
           </div>
         </v-flex>
         <v-flex xs12 >
           <v-container grid-list-xl fluid>
             <v-layout row wrap align-center>
               <v-flex xs12 md4>
                 <v-card >
                    <v-img
                      src="https://images.pexels.com/photos/196644/pexels-photo-196644.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Documentation</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.multisigcrypto.com/docs">Study</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md4>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/261662/pexels-photo-261662.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Blog</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.decentralizejustice.com/blog">Read</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md4>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/212286/pexels-photo-212286.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Business Plan</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.decentralizejustice.com/busi">Explore</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md4>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/546819/pexels-photo-546819.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Applications</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://github.com/DecentralizeJustice/">Github</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md4>
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/1537008/pexels-photo-1537008.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Technical Specification</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.multisigcrypto.com/spec/">Study</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
               <v-flex xs12 md4 >
                 <v-card>
                    <v-img
                      src="https://images.pexels.com/photos/707195/pexels-photo-707195.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
                      aspect-ratio="2"
                    ></v-img>
                  <v-card-title primary-title class="justify-center">
                    <div>
                      <h3 class="headline mb-0">Usage Instructions</h3>
                    </div>
                  </v-card-title>
                  <v-card-actions class="justify-center">
                    <v-btn flat color="orange" href="https://www.multisigcrypto.com/instruct/">Instructions</v-btn>
                  </v-card-actions>
                </v-card>
               </v-flex>
             </v-layout>
           </v-container>
         </v-flex>
       </v-layout>
     </section>

   </v-content>
   </v-container>
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
