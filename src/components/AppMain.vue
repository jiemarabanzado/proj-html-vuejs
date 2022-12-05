<script>
    import FirstMainSection from './FirstMainSection.vue'
    import {store} from '../store'
    export default{
        components:{
            FirstMainSection
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
    </main>
</template>

<style lang="scss" scoped>
    main{
    }
    
</style>