<script>
    import FootHeader from './FooterHeader.vue'
    import FooterMain from './FooterMain.vue'
    import {store} from '../store'
    export default{
       components:{
        FootHeader,
        FooterMain
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
    <div class="main-container">
        <FooterMain/>
    </div>
    

</template>

<style>

</style>