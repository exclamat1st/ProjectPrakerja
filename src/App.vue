<template>
  <v-app>
    <HeaderPage />
    <v-main>
      <HeroComponent />
      <AboutUs />
      <OurLocation />
      <GalleryG />
      <FooterF />
    </v-main>
  </v-app>
</template>

<script type="module">
import GalleryG from './components/Gallery.vue';
import HeaderPage from './components/Header.vue';
import HeroComponent from './components/HeroComponent.vue';
import AboutUs from './components/AboutUs.vue';
import OurLocation from './components/OurLocation.vue';
import FooterF from './components/Footer.vue';
export default {
  name: 'App',
  // eslint-disable-next-line vue/no-unused-components
  components: {HeroComponent, HeaderPage, AboutUs, OurLocation,GalleryG, FooterF },
    data (){
      return{
        menus:[
          { title:'Home',        route:'home'},
          { title:'About Us',    route:'about-us'},
          { title:'Location',    route:'location'},
          { title:'Gallery',     route:'gallery'},
    ]
    }
  }}
</script>
