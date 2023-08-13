<template>
    <v-row class="px-16 mt-10">
        <v-col cols="3" v-for="(partner,i) in partners" :key="i">
            <div class="" align="center" justify="center">
                <v-img :src="partner.img" max-width="80" max-height="80" contain></v-img>
            </div>
        </v-col>
    </v-row>
</template>
<script>
export default {
    data: () => ({
        partners: [
            {img: 'airbnb.png'},
            {img: 'adidas.png'},
            {img: 'swords.png'},
            {img: 'castle.png'},
        ]
    })
}
</script>
<style>
    
</style>