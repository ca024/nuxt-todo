<template>
        <v-row justify="center">
      <v-col
        cols="12"
        sm="7"
        md="6"
        lg="5"
      >
        <v-sheet
          elevation="10"
        >        
        </v-sheet> 
      </v-col>
      
    </v-row>
    <v-virtual-scroll
    :height="438"
    :items="['Learn Nuxt', 'Learn Vue', 'Learn Vuetify']"
  >
    <template v-slot:default="{ item }">
  
      <div class="elevation-6 pa-2 ma-2 text-center">
      <h3>{{ item }}</h3>
      </div>
    </template>
  </v-virtual-scroll>
</template>