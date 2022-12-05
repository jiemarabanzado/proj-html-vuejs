<script>
    import FirstMainSection from './FirstMainSection.vue'
    import SecondMainSection from './SecondMainSection.vue'
    import ThirdMainSection from './ThirdMainSection.vue'
    import {store} from '../store'
    export default{
        components:{
            FirstMainSection,
            SecondMainSection,
            ThirdMainSection
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
      

    </main>
</template>

<style lang="scss" scoped>
    main{
    }
    
</style>