<script>
    import FootHeader from './FooterHeader.vue'
    import {store} from '../store'
    export default{
       components:{
        FootHeader
       },
        data(){
            return{
                store
            }
        }
    }
</script>

<template>
    <FootHeader/>

</template>

<style>

</style>