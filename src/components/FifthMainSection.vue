<script>

</script>

<template>
    <section>
        <div class="exam-icon">
            <img src="../assets/img/Exam-icon.png" alt="">

        </div>
        <div class="method-row row">
            <div class="left-method">
                <h3>
                    The most efficient examination method
                </h3>
                <p>
                    EduPrime has gathered teachers from around the globe to brainstorm in order to facilitate the evaluation of our students. <br>
                    every teacher from our university has an influence on how students are evaluated at his/her subject
                </p>
                <div class="method-btn">
                    <button>Discover the method</button>
                </div>
            </div>
            <div class="right-method">
                <div class="method-img">
                    <img src="../assets/img/Exam-Illustration.png" alt="">
                </div>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    .exam-icon{
        width: 50px;
        img{
            width: 100%;
        }
    }
    .method-row{
        justify-content: space-between;
        align-items: center;
        width: 100%;
        .left-method{
            width: 50%;
            height: 100%;
            h3{
                font-size: 2.9rem;
                margin-bottom: 30px;
            }
            p{
                margin-bottom: 30px;
            }
            .method-btn{
                button{
                    padding: 15px 25px;
                    border-radius: 30px;
                    border: none;
                    color: white;
                    background-color: #e56768;
                }
            }
        }
        .right-method{
            width: 40%;
            .method-img{
                width: 100%;
                img{
                    width: 100%;
                }
            }
        }
    }
</style>