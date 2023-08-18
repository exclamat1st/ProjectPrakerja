<template>
    <v-container>
        <v-row>
            <v-col lg="6">
                <h2 class="intro-text">Selamat Datang di RESTORUN!</h2>
                <p class="description"> Kami Menyajikan Makanan Istimewa & Terbaik Untuk Anda</p>
                <v-btn color="success" class="pencet" rounded>Daftar Member</v-btn>
                <v-btn color="indigo" class="tombolbiru" rounded>Masuk</v-btn>
            </v-col>
            <v-col lg="6">
                <img src="./../assets/hero-img.jpg" class = "hero" alt="">
            </v-col>
        </v-row>
    </v-container>
</template>
<script>

    export default {    
        name: "HeroComponent"
    }
</script>

<style scoped>
    h2.intro-text {
        display : flex;
        text-align: justify;
        margin: 100px 100px 0px;
        font-size: 5em;
        font-weight: bold;
        font-family: serif;
        color : #514c4c;
    }
    p.description {
        display: flexbox;
        font-size: 39px;
        font-family: serif;
        margin: 20px 100px;
        color: #444444ba;
    }
    img.hero{
        border-radius : 10%;
        width : 128%;
        height: 110%;
        margin : 0px 0px 0px 0px;
    
    }
    .pencet {
        margin: 0px 0px 0px 100px;
        color: white;
    }
    .tombolbiru {
        margin: 0px 0px 0px 30px;
        color: white;
    }
</style>
