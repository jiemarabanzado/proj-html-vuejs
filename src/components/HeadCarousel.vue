<script>
    import { store } from '../store';
    export default{
        data(){
            return{
               store,
               activeSlide:2
            }
        },
        methods:{
            startInterval(){
               setInterval(this.changeSlide
               ,4000)
            },
            changeSlide(){
                if(this.activeSlide==2){
                    this.activeSlide=0
                }else{
                    this.activeSlide+=1;
                }

            }
        },
        created(){
            this.startInterval()
        }

    }
</script>

<template>
    <section class="carousel">
        <div class="img-container">
            <div class="slide" :class="(this.activeSlide==0 ? 'active':'')">
                <img src="../assets/img/theme_slider1_bg-1.jpg" alt="">
            </div>
            <div class="slide" :class="(this.activeSlide==1 ? 'active':'')">
                <img src="../assets/img/theme_slider2_bg-1.jpg" alt="">
            </div>
            <div class="slide" :class="(this.activeSlide==2 ? 'active':'')">
                <img src="../assets/img/theme_slider3_bg-1.jpg" alt="">
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    .carousel{
        bottom: 0;
        position: absolute;
        width: 100%;
        height: 100%;
        .img-container{
            width: 100%;
            position: relative;
            .slide{
                width: 100%;
                position: absolute;
                top: 0;
                bottom: 0;
                right: 0;
                left: 0;
                img{
                    width:100%;
                    object-fit: cover;
                }
            }
        }
    }
    .slide{
        opacity: 0;
    }
    .active{
        opacity: 1;
        z-index: 1;
    }

</style>