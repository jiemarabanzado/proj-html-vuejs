<script>
    export default{
        data(){
            return{
                activeTab:0
            }
        },
        methods:{
            ChangeActiveTab(tab){
                this.activeTab=tab;
            }
        }
    }
</script>

<template>
    <section>
        <h3>Faculties available at EduPrime</h3>
        <p class="first-p">A single university with load of courses, tailored <br> to satisfy any students need</p>
        <div class="faculties">
            <div class="faculties-row row main-container">
                <div class="faculty-container">
                    <div @click="ChangeActiveTab(0)" class="faculty row" :class="(activeTab==0 ? 'active-faculty':'')">
                        <div><img :class="(activeTab==0 ? 'active-faculty-img':'')" src="../assets/img/Gavel-v2.png" alt=""></div>
                    </div>
                    <div class="arrow" :class="(activeTab==0 ? 'active-arrow':'')" >
                        <i class="fa-solid fa-sort-down"></i>
                    </div>    
                </div>
                <div class="faculty-container">
                    <div @click="ChangeActiveTab(1)"  class="faculty row" :class="(activeTab==1 ? 'active-faculty':'')">
                        <div><img :class="(activeTab==1 ? 'active-faculty-img':'')"  src="../assets/img/Coins-tabs-v2.png" alt=""></div>
                    </div>
                    <div class="arrow" :class="(activeTab==1 ? 'active-arrow':'')">
                        <i class="fa-solid fa-sort-down"></i>
                    </div>    
                </div>
                <div class="faculty-container">
                    <div @click="ChangeActiveTab(2)"  class="faculty row" :class="(activeTab==2 ? 'active-faculty':'')">
                        <div><img :class="(activeTab==2 ? 'active-faculty-img':'')"  src="../assets/img/Medicine-tabs-v2.png" alt=""></div>
                    </div>
                    <div class="arrow" :class="(activeTab==2 ? 'active-arrow':'')">
                        <i class="fa-solid fa-sort-down"></i>
                    </div>    
                </div>
                <div class="faculty-container">
                    <div @click="ChangeActiveTab(3)"  class="faculty row" :class="(activeTab==3 ? 'active-faculty':'')">
                        <div><img :class="(activeTab==3 ? 'active-faculty-img':'')"  src="../assets/img/Computer-tabs-v2.png" alt=""></div>
                    </div>
                    <div class="arrow" :class="(activeTab==3 ? 'active-arrow':'')">
                        <i class="fa-solid fa-sort-down"></i>
                    </div>    
                </div>
                <div class="faculty-container">
                    <div @click="ChangeActiveTab(4)"  class="faculty row" :class="(activeTab==4 ? 'active-faculty':'')">
                        <div><img :class="(activeTab==4 ? 'active-faculty-img':'')"  src="../assets/img/Palette-tabs-v2.png" alt=""></div>
                    </div>
                    <div class="arrow" :class="(activeTab==4 ? 'active-arrow':'')">
                        <i class="fa-solid fa-sort-down"></i>
                    </div>    
                </div>
            </div>
        </div>
    </section>

</template>


<style lang="scss" scoped>
    section{
        height: 1000px;
    }
    h3{
        text-align: center;
        font-size: 2.9rem;
        margin-bottom: 25px;
    }
    .first-p{
        text-align: center;
        margin-bottom: 25px;
    }
    .faculties{
        height: 165px;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
        .faculties-row{
            height: 100%;
            width: 100%;
            
        }
    }
    .faculty-container{
            width: calc(100%/5);
            position: relative;
            border-left: 2px solid #eaeaea;
            &:last-child{
                border-right: 2px solid #eaeaea;
            }
            .faculty{
                height: 100%;
                align-items: center;
                justify-content: center;
                position: relative;
                div{
                    width: 60%;
                img{
                    width: 100%;
                }
                }
            
        }

    }
    
    .arrow{
        position: absolute;
        bottom: -15px;
        right: calc(50% - 10px);
        font-size: 2rem;
        color: #e56768;
        opacity: 0;
    }
    .active-arrow{
        opacity: 1;
    } 
    .active-faculty{
        background-color: #e56768;
    }
    .active-faculty-img{
        color: rgb(255, 255, 255);
        filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(312deg) brightness(107%) contrast(101%);
    }
</style>