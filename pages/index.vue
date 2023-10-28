<template>
      <v-main id="main">
        <v-container>
          <v-row>
            <Column />
            <v-col
              cols="12"
              md="8"
            >
              <Box />
            </v-col>
            <Column />
          </v-row>
        </v-container>
      </v-main>
  </template>
  
<script setup>
useHead({
    title: "To Do"
})

</script>
  
<style>
#com {
    color: #004225;
}
#del {
    color: #D80032;
}
#chip {
    background-color: whitesmoke;
    color: #176B87;
    font-weight: bold;

}
#main {
    background-color: #64CCC5;
}

#menu {
    background-color: #04364A;
}

#card {
    background-color: #DAFFFB;
}
</style>
