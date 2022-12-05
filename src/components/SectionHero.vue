<script>

</script>

<template>
    <section class="hero">
        <h2>Key to your success</h2>
        <p>EduPrime is the most versatile WordPress theme for educational porpuses, showcasing universities,courses,secondary schools etc.</p>
        <div class="hero-buttons">
            <button class="hero-btn"><span></span>Search courses</button>
            <button class="hero-btn"><span></span>Apply for university</button>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    .hero{
        z-index: 1;
        max-width: 620px;
        padding: 20px 20px;
        margin: auto;
        color: white;
        h2{
            text-align: center;
            font-size: 3.1rem;
            margin-bottom: 35px;
        }
        p{
            text-align: center;
            font-size: 1.05rem;
            margin-bottom: 40px;
        }
        .hero-buttons{
            text-align: center;
            .hero-btn{
                margin: 0px 15px;
                padding: 17px 25px;
                border-radius: 25px;
                border: none;
                &:first-child{
                    color: white;
                    background-color:#E9D758;

                }
                &:nth-child(2){
                    background-color: white;
                    color: #E56768;
                }

            }
        }
    }
</style>