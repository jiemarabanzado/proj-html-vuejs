<script>
    import FirstMainSection from './FirstMainSection.vue'
    import SecondMainSection from './SecondMainSection.vue'
    import ThirdMainSection from './ThirdMainSection.vue'
    import FourthMainSection from './FourthMainSection.vue'
    import FifthMainSection from './FifthMainSection.vue'
    import SixthMainSection from './SixthMainSection.vue'
    import {store} from '../store'
    export default{
        components:{
            FirstMainSection,
            SecondMainSection,
            ThirdMainSection,
            FourthMainSection,
            FifthMainSection,
            SixthMainSection
        },
        data(){
            return{
                store
            }
        }
    }
</script>

<template>
    <main>
        <div class="first-main-sec">
            <div class="main-container">
                <FirstMainSection/>
            </div>
        </div>
        <SecondMainSection/>
        <ThirdMainSection/>
        
        <div class="main-container">
            <FourthMainSection/>
        </div>
    
        
        <div class="main-container">
            <FifthMainSection/>
            <SixthMainSection/>
        </div>
      

    </main>
</template>

<style lang="scss" scoped>
    .first-main-sec{
        background-image: url('../assets/img/home-background.png');
        background-size: cover;
        background-position: top;
    }   
</style>