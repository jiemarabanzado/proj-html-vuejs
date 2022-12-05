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
    <div>main</div>
    <div>{{this.store.temp}}</div>

</template>

<style>

</style>