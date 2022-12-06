<script>
    import { store } from '../store';
    import SectionHero from './SectionHero.vue'
    import HeadCarousel from './HeadCarousel.vue'
    export default{
        components:{
            SectionHero,
            HeadCarousel
        },
        data(){
            return{
                store
            }
        }
    }
</script>

<template>
    <div class="head-container">
        <div class="left-icon">
            <div><i class="fa-solid fa-cart-shopping"></i></div>
            <div><i class="fa-solid fa-book-open"></i></div>
            <div><i class="fa-regular fa-life-ring"></i></div>
        </div>
        <HeadCarousel/>
        <header>
        <div class="head-bar container row">
            <div class="head-img">
                <img src="../assets/img/theme_eduprime_logo.png" alt="">
            </div>
            <div class="head-nav">
                <ul class="row">
                    <li class="dropdown-nav row">
                        <div>Home</div>
                        <div><i class="fa-solid fa-sort-down"></i></div>
                    </li>
                    <li class="dropdown-nav row">
                        <div>Courses</div>
                        <div><i class="fa-solid fa-sort-down"></i></div>
                    </li>
                    <li>About us</li>
                    <li class="dropdown-nav row">
                        <div>News</div>
                        <div><i class="fa-solid fa-sort-down"></i></div>
                    </li>
                    <li class="dropdown-nav row">
                        <div>Pages</div>
                        <div><i class="fa-solid fa-sort-down"></i></div>
                    </li>
                    <li>Contact</li>
                    <li>Purchase</li>
                </ul>
            </div>
            <div class="head-btn">
                <button>VIEW COURSES</button>
            </div>
        </div>
        <SectionHero/>
        
        
        <!--<div class="header-svg"><img src="../assets/svg/svg-1.svg" alt=""></div>-->    
    </header>
    </div>
    
    
</template>

<style lang="scss" scoped>
    .left-icon{
        position: absolute;
        left: 0;
        bottom: 35%;
        border-top-right-radius: 5px;
        border-bottom-right-radius: 5px;
        z-index: 30;
        background-color: #E9D758;
        div{
            padding: 9px;
            color: white;
            font-size: 0.8rem;
        }

    }
    .head-container{
        height: 540px;
        overflow-y: hidden;
        position: relative;
    }
    .head-container::after{
        content: '';
        background-image: url(../assets/img/Wave-1.png);
        background-size: cover;
        height: 90px;
        position: absolute;
        z-index: 100;
        bottom: 0;
        right: 0;
        left: 0;
    }
    header{
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        background-color: #da5f5fd9;
        padding:25px 0px;
        position:absolute;
        overflow: hidden;
        z-index: 2;
        .head-bar{
            align-items: center;
            margin-bottom: 60px;
        }
        
    }
    .head-img{
        flex-grow: 1;
        cursor: pointer;
        img{
            width: 280px;
            object-fit: cover;
        }
    }
    ul{
        align-items: center;
        li{
            list-style: none;
            margin-right: 20px;
            color: white;
            cursor: pointer;
            font-family: 'Fredoka One', cursive;
            &:first-child{
                color:#e8d259;
            }
            
        }
    }
    .dropdown-nav div{
        margin-right: 5px;
        font-family: 'Fredoka One', cursive;
    }
    .dropdown-nav{
        align-items: center;
        
    }
    .dropdown-nav i{
        font-size: 0.8rem;
        padding-bottom: 6px;
    }
    button{
        padding: 20px;
        font-weight: 400;
        font-size: 0.8rem;

        background-color: #E9D758;
        border: none;
        border-radius: 30px;
        color: white;
        &:hover{
            background-color: white;
            color: #e56768;
        }
    }
    
</style>