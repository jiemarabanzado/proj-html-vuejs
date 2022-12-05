<script>
    import { store } from '../store';
    export default{
        data(){
            return{
                store
            }
        }
    }
</script>

<template>
    <header>
        <div>header</div>
        <div>{{this.store.temp}}</div>
    </header>

</template>

<style>

</style>