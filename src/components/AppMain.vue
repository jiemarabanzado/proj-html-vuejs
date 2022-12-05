<script>
    import FirstMainSection from './FirstMainSection.vue'
    import SecondMainSection from './SecondMainSection.vue'
    import {store} from '../store'
    export default{
        components:{
            FirstMainSection,
            SecondMainSection
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
    </main>
</template>

<style lang="scss" scoped>
    main{
    }
    
</style>