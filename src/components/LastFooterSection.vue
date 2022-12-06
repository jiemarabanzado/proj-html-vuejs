<script>

</script>

<template>
    <section>
        <div class="foot-nav main-container row">
            <div class="left-foot">
                <div class="foot-logo">
                    <img src="../assets/img/theme_eduprime_logo.png" alt="">
                </div>
                <p>EduPrime is the most versatile WordPress theme for educational porpuses, showcasing universities,courses,secondary schools etc.</p>
                <button class="social"><i class="fa-brands fa-facebook-f"></i></button>
                <button class="social"><i class="fa-brands fa-twitter"></i></button>
                <button class="social"><i class="fa-brands fa-instagram"></i></button>
            </div>
            <div class="center-foot row">
                <div class="left-nav">
                    <h4>Get EduPrime</h4>
                    <ul>
                        <li>Request a website</li>
                        <li>Browse Themes</li>
                        <li>Payment options</li>
                        <li>Support system</li>
                        <li>Checkout</li>
                        <li>Purchase theme</li>
                    </ul>
                </div>
                <div class="right-nav">
                    <h4>Get EduPrime</h4>
                    <ul>
                        <li>Purchase theme</li>
                        <li>Our Benefits</li>
                        <li>Our Theme</li>
                        <li>Our Services</li>
                        <li>Other Products</li>
                        <li>My account</li>
                    </ul>
                </div>
            </div>
            <div class="right-foot">
                <div class="foot-search">
                    <input type="text" placeholder="Search...">
                    <button class="foot-btn"><i class="fa-solid fa-magnifying-glass"></i></button>
                </div>
                <h4>Search categories</h4>
                <div class="tags">
                    <button class="tag-btn">ECONOMY</button>
                    <button class="tag-btn">DESIGN</button>
                    <button class="tag-btn">COACHING</button>
                    <button class="tag-btn">BUSINESS</button>
                    <br>
                    <button class="tag-btn">ECONOMY</button>
                    <button class="tag-btn">DESIGN</button>
                    <button class="tag-btn">ECONOMY</button>
                </div>
                <div style="text-align:end">
                    <small class="rights">
                        ModelTheme. All rights reserved
                    </small>
                </div>
            </div>
        </div>
        <button class="chevron"><i class="fa-solid fa-chevron-up"></i></button>
        
        
        <button class="top-btn">
            <div class="btn-row row">
                <div>
                    <img class="img-btn" src="../assets/svg/svg-3.svg" alt="">
                </div>
                <div>Purchase Theme</div>
            </div>
        </button>
       
        
        <button class="bottom-btn">
            <div class="btn-row row">
                <div>
                    <img class="img-btn" src="../assets/svg/svg-2.svg" alt="">
                </div>
                <div>Related Themes</div>
                
            </div>
        </button>
        
            
        
    </section>

</template>

<style lang="scss" scoped>
    .top-btn{
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        position: absolute;
        width: 180px;
        height: 40px;
        background-color: #454545;
        border: none;
        border-radius: 5px;
        color: #c3c3c3;
        margin-bottom: 13px;  
        left: 3%;
        bottom: 16%;   
    }
    .bottom-btn{
        position: absolute;
        left: 3%;
        bottom: 7%;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        width: 180px;
        height: 40px;
        background-color: #454545;
        border: none;
        border-radius: 5px;
        color: #c3c3c3;
    }
    .btn-row{
        padding-left: 13px;
        align-items: center;
    }
    
    .img-btn{
        width:15px;
        margin-right: 5px;
    }
    section {
        background-color: #e56768;
        padding-top: 120px;
        padding-bottom: 90px;
        position: relative;
        .chevron{
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: #e9d758;
            border: none;
            color: white;
            font-size: 1.1rem;
            position: absolute;
            right: 5%;
            bottom: 7%;
        }
        
            
    
        .foot-nav{
            justify-content: space-between;
            .left-foot{
                width: 30%;
                height: 100%;
                .foot-logo{
                    width: 100%;
                    margin-bottom: 30px;
                    img{
                        width: 80%;
                    }
                }
                p{
                    color: white;
                    margin-bottom: 30px;
                }
                
            }
        }
    }
    .social{
        width: 40px;
        height: 40px;
        border-radius: 50%;
        background-color: transparent;
        color: white;
        border: 2px solid #e9d758;
        margin-right: 10px;
        
    }
    .center-foot{
        width: 30%;
        justify-content: space-between;
        .left-nav{
            color: white;
            width: calc(100%/2 - 10px);
            h4{
                margin-bottom: 25px;
                font-size: 1.2rem;
                
            }
        }
    }
    ul{
        li{
            list-style: none;
            margin-bottom: 13px;
        }
    }
    .right-nav{
        color: white;
        width: calc(100%/2 - 10px);
        h4{
            margin-bottom: 25px;
            font-size: 1.2rem;
            
        }
    }
    .right-foot{
        width: 35%;
        .foot-search{
            width: 100%;
            height: 50px;
            position: relative;
            margin-bottom: 30px;
            input{
                width: 100%;
                height: 100%;
                border-radius: 30px;
                border: none;
            }
            .foot-btn{
                width: 50px;
                height: 50px;
                border-radius: 50%;
                color: white;
                border: none;
                background-color: #e9d758;
                position: absolute;
                bottom: 0;
                right: 0;
            }
        }
        h4{
            font-size: 1.1rem;
            color: white;
            text-align: end;
            margin-bottom: 25px;
        }
        .tags{
            text-align: end;
            .tag-btn{
                font-size: 0.6rem;
                margin-right: 7px;
                border-radius: 20px;
                color: white;
                background-color: transparent;
                border: 1px solid white;
                padding: 7px 12px;
                margin-bottom: 15px;
            }
        }
    }
    .rights{
        color: #e9d758;
    }

</style>