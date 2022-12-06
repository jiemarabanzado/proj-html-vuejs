<script>

</script>

<template>
    <section>
        <div class="book-icon">
            <img src="../assets/img/Books-icon.png" alt="">
        </div>
        <div class="first-section-row row">
            <div>
                <h3>Thousands of courses for any type of student</h3>
                <p>At EduPrime, it doesn't matter what domain you widh to pursue a career in. Here you can find a course that satisfies your needs withina click away and applies for a course in a matter of minutes.EduPrime is ranked as the most versatile university in the world,thanks to the number of courses it provides</p>
                <div>
                    <button>Browse through courses</button>
                </div>
            </div>
            <div class="right-column">
                <div class="right-img">
                    <img src="../assets/img/Graduation-Illustration.png" alt="">
                </div>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    section{
        padding: 100px 0px;
        .book-icon{
            width: 70px;
            margin-bottom: 15px;
            img{
                width: 100%;
            }
        }
        .first-section-row{
            width: 100%;
            justify-content: space-between;
            align-items: center;
            div:first-child{
                width: 51%;
               
                h3{
                    font-size: 2.5rem;
                    margin-bottom: 30px;
                }
                p{
                    margin-bottom: 30px;
                }
            }
            .right-column{
                width: 40%;
                .right-img{
                    width: 100%;
                    img{
                        width: 100%;
                    }
                }
            }
        }
        
    }
    button{
        padding: 20px 25px;
        border-radius: 30px;
        border: none;
        color: white;
        background-color: #E9D758;
    }
</style>