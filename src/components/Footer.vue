<template>
    <v-footer dark padless>
        <v-card flat tile class="black white--text py-12 px-5" width="100%">
            <v-row>
                <v-col cols="12" xs="12" sm="6" md="4" class="pa-16">
                    <v-toolbar color="transparent" flat>
                        <v-badge color="#D5F0DB" dot>
                            <v-img src="1.png" contain width="30"></v-img>
                        </v-badge>
                        <v-toolbar-title class="ml-4">
                            <span class="green--text">e</span><strong>Grocery</strong>
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="pt-0">
                        <v-btn v-for="icon in icons" :key="icon" class="mx-1 white--text" icon fab outlined small>
                            <v-icon size="20px">
                                {{ icon }}
                            </v-icon>
                        </v-btn>
                    </v-card-text>
                </v-col>
                <v-col cols="12" xs="12" sm="6" md="4">
                    <v-card-text class="white--text pt-0">
                        <h3>About</h3>
                    </v-card-text>
                    <v-card-text class="grey--text mt-n4">How it works</v-card-text>
                    <v-card-text class="grey--text mt-n4">Our Programs</v-card-text>
                    <v-card-text class="grey--text mt-n4">Promotions</v-card-text>
                    <v-card-text class="grey--text mt-n4">Refer A Friend</v-card-text>
                </v-col>       
                <v-col cols="12" xs="12" sm="6" md="4">
                    <v-card-text class="white--text pt-0">
                        <h3>Our Site</h3>
                    </v-card-text>
                    <v-card-text class="grey--text mt-n4">About Us</v-card-text>
                    <v-card-text class="grey--text mt-n4">Careers</v-card-text>
                    <v-card-text class="grey--text mt-n4">Terms & Condition</v-card-text>
                    <v-card-text class="grey--text mt-n4">Refund Policy</v-card-text>
                </v-col>       
            </v-row>
        </v-card>
    </v-footer>
</template>
<script>
export default {
    data: () => ({
        icons: [
            "fab fa-apple",
            "fab fa-google-play",
            "fab fa-twitter",
            "fab fa-facebook-f"
        ]
    })
}
</script>
<style>
    
</style>