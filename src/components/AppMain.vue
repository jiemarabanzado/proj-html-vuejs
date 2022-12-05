<script>
    import FirstMainSection from './FirstMainSection.vue'
    import SecondMainSection from './SecondMainSection.vue'
    import ThirdMainSection from './ThirdMainSection.vue'
    import FourthMainSection from './FourthMainSection.vue'
    import FifthMainSection from './FifthMainSection.vue'
    import {store} from '../store'
    export default{
        components:{
            FirstMainSection,
            SecondMainSection,
            ThirdMainSection,
            FourthMainSection,
            FifthMainSection
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
        <div class="main-container">
            <FirstMainSection/>
        </div>
        <SecondMainSection/>
        <ThirdMainSection/>
        <div class="main-container">
            <FourthMainSection/>
            <FifthMainSection/>
        </div>
      

    </main>
</template>

<style lang="scss" scoped>
    main{
    }
    
</style>