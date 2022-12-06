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
    <div class="temp-sec">
        <div class="main-container">
            <FooterMain/>
        </div>
    </div>
    
    <LastFooterSection/>

</template>

<style lang="scss" scoped>
    .temp-sec{
        position: relative;
        background-color: #fafafa;
        &::after{
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            background-image: url('../assets/img/background-wave3.png');
            background-size: cover;
            height: 100%;
            transform: rotate(180deg);

        }
    }

</style>