<template>
    <v-container class ="my-15">
        <v-row justify="center">
            <v-col lg="12" class="text-center">
                <v-subheader class="lokasi5">Our Location</v-subheader>
                <p class="lokasi1">Berikut Lokasi Restoran Kami:</p>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d63458.467294594164!2d106.77754000134686!3d-6.243398948622111!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f1774d7d38ff%3A0x2ce17918884152a0!2sJakarta%20Restaurant%20%26%20The%20Courtyard!5e0!3m2!1sen!2sid!4v1692366401142!5m2!1sen!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </v-col>

        </v-row>
    </v-container>
</template>

<script>

export default {    
        name: "OurLocation"
    }
</script>

<style>
.lokasi5 {
    text-align: center;
    font-weight: bold;
    margin:200px 0px 0px 0px;
    font-family: serif;
    font-size: 90px;
}
.lokasi1{
    text-align: center;
    margin:50px 0px 0px 0px;
    font-family: serif;
    font-size: 30px;
}
.maps{
    border-radius: 10%;
    width: 100%;
    align-items: center;
}
</style>