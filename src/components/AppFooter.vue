<script>
    import FootHeader from './FooterHeader.vue'
    import FooterMain from './FooterMain.vue'
    import LastFooterSection from './LastFooterSection.vue'
    import {store} from '../store'
    export default{
       components:{
        FootHeader,
        FooterMain,
        LastFooterSection
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
    <LastFooterSection/>

</template>

<style>

</style>