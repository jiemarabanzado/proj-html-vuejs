<script>
    import {store} from '../store'
    export default{
       
        data(){
            return{
                store
            }
        }
    }
</script>

<template>
    <div>footer</div>
    <div>{{this.store.temp}}</div>

</template>

<style>

</style>