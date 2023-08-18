<template>
    <v-app-bar
        style="padding: 0px 30px"
        app
        color="black"
        dark 
        elevation="6"
        elevate-on-scroll
>
<v-toolbar-title>
  <img class="imglogo" src="./../assets/Restorunlogo.png" alt="">
</v-toolbar-title>
<v-spacer />

<v-list class="d-flex align-center">
  <v-list-item link v-for="(menu,index) in menus" :key="index" :to="menu.route">
    <v-list-item-title>{{menu.title}}</v-list-item-title>
  </v-list-item>
  <v-btn text>
    <v-icon>mdi-magnify</v-icon>
  </v-btn>
  <v-btn @click="scrollToElement" outlined color="sucess">Jadilah Member
  </v-btn>
</v-list>

</v-app-bar>
</template>

<script>
    export default {
        name: "HeaderPage",
        data(){
          return{
              menus:[
                {title:'Home',          route:'home'},
                {title:'About Us',      route:'about-us'},
                {title:'Our Location',  route:'location'},
                {title:'Gallery',       route:'gallery'},
      ]
    }
  }
};

</script>

<style scoped>
  .imglogo {
    width : 40%;
  }
  .v-toolbar-title {
    font-size: 32px;
    color: #4caf50;
    font-weight: 700;
    font-family: cursive;
  }
</style>
