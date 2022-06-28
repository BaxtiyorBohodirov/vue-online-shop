<template>
    <div class="v-catalog-item">
        <p>Cart title</p>
        <p>Price:20000</p>
        <button>Add to cart</button>
    </div>
</template>


<script>
export default {
    name:'v-catalog-item',
    props:{},
    data(){
        return{}
    },
}
</script>

<style lang="sass">
    .v-catalog-item
    {
        color: $red;
    }
</style>