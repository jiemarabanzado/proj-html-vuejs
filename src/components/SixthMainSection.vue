<script>

</script>

<template>
    <section>
        <div class="fees-row row">
            <div class="right-fees">
                <div class="fees-img">
                    <img src="../assets/img/Girl-Illustration.png" alt="">
                </div>
            </div>
            <div class="left-fees">
                <div class="exam-icon">
            <img src="../assets/img/Exam-icon-1.png" alt="">

        </div>
                <h3>
                    Variable fees for international students
                </h3>
                <p>
                    EduPrime has gathered teachers from around the globe to brainstorm in order to facilitate the evaluation of our students. <br>
                    every teacher from our university has an influence on how students are evaluated at his/her subject
                </p>
                <div class="fees-btn">
                    <button>list of fees</button>
                </div>
            </div>
        </div>
    </section>

</template>


<style lang="scss" scoped>
    section{
        margin-bottom: 80px;
    }
    .exam-icon{
        width: 50px;
        img{
            width: 100%;
        }
    }
    .fees-row{
        justify-content: space-between;
        align-items: center;
        width: 100%;
        .left-fees{
            width: 50%;
            height: 100%;
            h3{
                font-size: 2.9rem;
                margin-bottom: 30px;
            }
            p{
                margin-bottom: 30px;
            }
            .fees-btn{
                button{
                    padding: 15px 25px;
                    border-radius: 30px;
                    border: none;
                    color: white;
                    background-color: #e56768;
                }
            }
        }
        .right-fees{
            width: 40%;
            .fees-img{
                width: 100%;
                img{
                    width: 100%;
                }
            }
        }
    }
</style>