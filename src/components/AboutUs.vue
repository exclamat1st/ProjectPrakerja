<template>
    <v-container>
        <v-row>
            <v-col lg="6">
                <img class ="img2" src="./../assets/aboutus.jpg" alt="">
            </v-col>
            <v-col>
                <v-subheader class="aboutus1">About Us</v-subheader>

                <p class="aboutus2">Sejak 1999, Restorun merupakan restoran yang menyajikan hidangan berkualitas tinggi & istimewa untuk pelanggan kami. Kami menjamin kualitas dan mutu dari hidangan yang kami sajikan. Kami selalu berusaha menciptakan variasi dan kreasi hidangan untuk pelanggan kita tercinta. </p>
                <p class="aboutus3">Resep hidangan kami telah menjadi pelopor sejak 1999 sehingga hidangan kami adalah andalan kami untuk memberikan cita rasa luar biasa kepada pelanggan kami. </p>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
    export default {
        name : "AboutUs"
    }
</script>

<style>
.img2 {
    border-radius : 10%;
    width : 108%;
    height: 90%;
    margin : 190px 0px 0px -150px;
}
.aboutus1 {
    font-weight: bold;
    color: #886161;
    margin : 200px 0px 0px 0px; 
    font-family: serif;
    font-size: 80px;
}
.aboutus2 {
    text-align: justify;
    font-family: serif;
    font-size: 30px;
    margin : 50px 0px 0px 30px;
}
.aboutus3 {
    text-align: justify;
    font-family: serif;
    font-size: 30px;
    margin : 0px 50px 0px 30px;
}
</style>