<template>
    <v-footer style="margin-top: 500px;" padless>
        <v-col lg="12">
            <v-row justify="center">
                <v-col lg="4" class="text-center">
                    <v-toolbar-title style="font-family:serif"
                    >Restorun</v-toolbar-title>
                    <v-card-text>
                        <v-btn 
                            v-for="icon in icons"
                            :key="icon"
                            class="mx-4 black--text"
                            icon
                            >
                        <v-icon size="24px">
                            {{ icon }}
                        </v-icon>
                        </v-btn>
                    </v-card-text>
                    <v-subheader style="margin:0px 10px 0px 240px">All rights reserved</v-subheader>
                    <v-form>
                        <v-text-field label="Email" outlined dense />
                        <v-btn rounded style="color:white" color=#212121>Subscribe Us</v-btn>
                    </v-form>
                </v-col>
            </v-row>
        </v-col>
        <v-card
            flat
            tile
            class="indigo lighten-1 white--text text-center">
        </v-card>
      <div>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          :icon="icon"
          variant="text"
        ></v-btn>
      </div>
  
      <div class="pt-0">
        copyright
    </div>
  
      <v-divider></v-divider>
  
      <div>
        {{ new Date().getFullYear() }} — <strong>Restorun</strong>
      </div>
    </v-footer>
  </template>
<script>
export default {
    name : "FooterF",
    data(){
        return{
            icons:[
                'mdi-facebook',
                'mdi-twitter',
                'mdi-linkedin',
                'mdi-instagram',
            ],
        }
    }
}
</script>