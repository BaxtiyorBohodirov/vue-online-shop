<template>
    <div class="main-wrapper">
        <h1>{{title}}</h1>
        <v-cart/>
        <v-catalog/>
    </div>

</template>

<script>
 import VCart  from "./v-cart.vue"
import VCatalog from './v-catalog.vue'

export default {
    name:'v-main-wrapper',
    components:{VCart, VCatalog},
    props:{},
    data(){
        return {
            title:"This is a title of main wrapper component"
        }

    },
}
</script>

<style>

</style>