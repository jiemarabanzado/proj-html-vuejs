<script>

</script>

<template>
    <section>
        <h3>Latest Courses</h3>
        <div class="courses-row row">
            <div class="course">
                <div class="course-img">
                    <img src="../assets/img/Decisions-icon.png" alt="">
                </div>
                <h4>Make Better Decisions</h4>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-user"></i>
                    </div>
                    <div class="who">
                        <small>
                            Teacher: <strong>James Collins</strong>
                        </small>
                    </div>
                </div>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-money-bill-1"></i>
                    </div>
                    <div class="who">
                        <small>
                            Price: <strong>$21.00</strong>
                        </small>
                    </div>
                </div>
                <div class="course-btn">
                    <button><i class="fa-solid fa-eye"></i>View course</button>
                </div>
            </div>
            <div class="course">
                <div class="course-img">
                    <img src="../assets/img/Speaker-icon.png" alt="">
                </div>
                <h4>How to be a speaker</h4>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-user"></i>
                    </div>
                    <div class="who">
                        <small>
                            Teacher: <strong>James Collins</strong>
                        </small>
                    </div>
                </div>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-money-bill-1"></i>
                    </div>
                    <div class="who">
                        <small>
                            Price: <strong>Free</strong>
                        </small>
                    </div>
                </div>
                <div class="course-btn">
                    <button><i class="fa-solid fa-eye"></i>View course</button>
                </div>
            </div>
            <div class="course">
                <div class="course-img">
                    <img src="../assets/img/Network-icon.png" alt="">
                </div>
                <h4>Network introductions</h4>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-user"></i>
                    </div>
                    <div class="who">
                        <small>
                            Teacher: <strong>James Collins</strong>
                        </small>
                    </div>
                </div>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-money-bill-1"></i>
                    </div>
                    <div class="who">
                        <small>
                            Price: <strong>Free</strong>
                        </small>
                    </div>
                </div>
                <div class="course-btn">
                    <button><i class="fa-solid fa-eye"></i>View course</button>
                </div>
            </div>
            <div class="course">
                <div class="course-img">
                    <img src="../assets/img/Brand-icon.png" alt="">
                </div>
                <h4>Brand manegement</h4>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-user"></i>
                    </div>
                    <div class="who">
                        <small>
                            Teacher: <strong>James Collins</strong>
                        </small>
                    </div>
                </div>
                <div class="teacher row">
                    <div class="teacher-icon">
                        <i class="fa-regular fa-money-bill-1"></i>
                    </div>
                    <div class="who">
                        <small>
                            Price: <strong>Free</strong>
                        </small>
                    </div>
                </div>
                <div class="course-btn">
                    <button><i class="fa-solid fa-eye"></i>View course</button>
                </div>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    section{
        padding: 90px 0px;
        position: relative;
    }
    
    h3{
        font-size: 2.5rem;
        margin-bottom: 50px;
    }
    .courses-row{
        width: 100%;
        justify-content: space-between;
        .course{
            position: relative;
            box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
            width: calc(100%/4 - 20px); 
            padding: 20px;
            .course-img{
                width: 45%;
                margin: auto;
                padding-bottom: 10px;
                img{
                    width: 100%;
                }
            }
            h4{
                font-size: 0.95rem;
                text-align: center;
                margin-bottom: 7px;
            }
            .teacher{
                justify-content: center;
                color: #5c5e6c;
                margin-bottom: 7px;
                align-items: center;
                .teacher-icon{
                    margin-right: 5px;
                }
                .who{
                    
                }

            }
        }
    }
    .course-btn{
        position: absolute;
        left: 22%;
        bottom: -10%;
        button{
            color: white;
            padding: 10px 15px;
            background-color: #e56768;
            border:none;
            border-radius: 30px;
        }
    }
</style>