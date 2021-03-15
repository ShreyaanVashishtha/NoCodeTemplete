<template>
  <main>
   <h1 class="section-title">
   About
   </h2>
     <p class="pa-md-4 mx-lg-auto" >    Killed by Google. There's a lot of them! By Shreyaan Vashishtha</p>
    <p class="font-italic">
        KilledByGoogle is an Open-Source Project and can be found on <a href = "https://github.com/ShreyaanVashishtha/NoCodeTemplete"> GitHub.</a>
    </p>
    <v-btn
    color = "primary"
    depressed
    elevation = "24"
    large
    medium
    small
    x-large
    x-small
    ><a href = "https://killedbygoogle.info">Home</a></v-btn>
 
 
 <template>
  <v-card
    class="mx-auto"
    color="#26c6da"
    dark
    max-width="400"
  >
    <v-card-title>
      <v-icon
        large
        left
      >
        mdi-twitter
      </v-icon>
      <span class="title font-weight-light">Twitter</span>
    </v-card-title>

    <v-card-text class="headline font-weight-bold">
      This is the Official Twitter Account for KilledByGoogle.Info
    </v-card-text>

    <v-card-actions>
      <v-list-item class="grow">
        <v-list-item-avatar color="grey darken-3">
          <v-img
            class="elevation-24"
            alt=""
            src="https://killedbygoogle.info/images/logos/icon.png"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title>GoogleKilled</v-list-item-title>
        </v-list-item-content>

        <v-row
          align="center"
          justify="end"
        >
          <v-icon class="mr-1">
            mdi-heart
          </v-icon>
          <span class="subheading mr-2">256</span>
          <span class="mr-1">·</span>
          <v-icon class="mr-1">
            mdi-share-variant
          </v-icon>
          <span class="subheading">45</span>
        </v-row>
      </v-list-item>
    </v-card-actions>
  </v-card>
</template>
    
    <script>
import TheHeader from '~/components/TheHeader.vue'

export default {
  name: 'Index',
  components: {
    TheHeader
    },
   </main>
</template>
