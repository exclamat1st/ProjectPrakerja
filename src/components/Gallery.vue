<template>
    <v-container class="carou">
    <v-row>
        <v-col>
            <v-subheader>
                <h2 class="Gal1">Gallery</h2>
            </v-subheader>
        </v-col>
 <v-carousel hide delimiter>       
  <v-carousel-item
    src="./../assets/img1.jpg"
    cover
  ></v-carousel-item>

  <v-carousel-item
    src="./../assets/img2.jpg"
    cover
  ></v-carousel-item>

  <v-carousel-item
    src="./../assets/img3.jpg"
    cover
  ></v-carousel-item>
</v-carousel>
    </v-row>
    </v-container>

</template>

<script>
    export default {
        name : "GalleryG"
    }
</script>

<style>
.carou {
    text-align: center;
    margin: 250px 0px 0px 500px;
    width:50%;
    height: 160px;
}
.Gal1 {
        text-align: center;
        display : flex;
        text-align: justify;
        margin: -50px 0px 0px 320px;
        font-size: 5em;
        font-weight: bold;
        font-family: serif;
        color : #514c4c;
}

</style>