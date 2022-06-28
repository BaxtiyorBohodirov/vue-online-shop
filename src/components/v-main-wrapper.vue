<template>
    <div class="main-wrapper">
        <h1>{{title}}</h1>
    </div>
</template>

<script>
export default {
    name:'v-main-wrapper',
    components:{

    },
    props:{},
    data(){
        return {
            title:"This is a title of main wrapper component"
        }

    },
    computed:{
        
    },
    methods:{

    },
    mounted(){
        console.log("Hello i am alive!");
    }
}
</script>

<style>

</style>