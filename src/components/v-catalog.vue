<template>
    <div class="v-catalog">
        <h1>
            Hello world
        </h1>
        <v-catalog-item/>
        <v-catalog-item/>
        <v-catalog-item/>
        <v-catalog-item/>
        <v-catalog-item/>
    </div>
</template>


<script>

import vCatalogItem from './v-catalog-item.vue'


export default {
  components: { vCatalogItem },
    name:'v-catalog',
    props:{},
    data(){
        return{
            title:"Catalog",
        }
    },
}
</script>


<style>

</style>