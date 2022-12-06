<script>

</script>

<template>
    <section>
        <div class="time-section main-container">
            <div class="bell row">
                <div class="bell-img">
                    <img src="../assets/img/Clock-and-Bell.png" alt="">
                </div>
            </div>
            <h3 class="uni-year">University year</h3>   
        </div>
        <div class="timeline">
            <div class="timeline-img">
                <img src="../assets/img/Timeline-Item.png" alt="">
            </div>
            <div class="orientation">
                <h4>Orientation</h4>
                <p>First day of university year, all students gather for the opening ceremony and then network with others.</p>
            </div>
            <div class="demo">
                <h4>Demo classes</h4>
                <p>In the first week,students try to accomodate with the teaching style and choose their optional courses.</p>
            </div>
            <div class="evaluation">
                <h4>Evaluation</h4>
                <p>At the end of a semester, students take a general evaluation test for every subject they're learning.</p>
            </div>
            <div class="graduation">
                <h4>Graduation</h4>
                <p>On the day of graduation , all students gather for the ceremony and then network and party among others.</p>
            </div>
        </div>
        <div class="time-section main-container">
            <div class="bell row">
                <div class="bell-img">
                    <img src="../assets/img/upcoming-events-calendar-icon.png" alt="">
                </div>
            </div>
            <h3 class="upcoming">Upcoming Events</h3>   
            <div class="events row">
                <div class="event">
                    <h4>Coaching Session</h4>
                    <small><span><i class="fa-solid fa-calendar-days"></i></span>20 May 21:30 pm</small>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi ù[...]</p>
                    <div class="more">
                        <button>+ find more</button>
                    </div>
                </div>
                <div class="event">
                    <h4>Coaching Session</h4>
                    <small><span><i class="fa-solid fa-calendar-days"></i></span>24 Mar 18:00 pm</small>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi ù[...]</p>
                    <div class="more">
                        <button>+ find more</button>
                    </div>
                </div>
                <div class="event">
                    <h4>Coaching Session</h4>
                    <small><span><i class="fa-solid fa-calendar-days"></i></span>12 Feb 13:30 pm</small>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi ù[...]</p>
                    <div class="more">
                        <button>+ find more</button>
                    </div>
                </div>
            </div>
            <div class="view-all">
                <button>View all events</button>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
    section{
        background-color: #e56768;
        padding: 150px 0px;
        .time-section{
            height: 100%;
            .uni-year{
                width: 299px;
                margin: auto;
                font-size: 2.5rem;
                background-color: #db2a2c;
                color: white;
                margin-bottom: 180px;
                
                
            }
        }

    }
    .bell{
        justify-content: center;
        margin-bottom: 20px;
    }
    .bell-img{
        width: 60px;
        img{
            width: 100%;
        }
    }
    .timeline{
        position: relative;
        margin-bottom: 160px;
        .timeline-img{
            max-width: 1000px;
            margin: auto;
        }
    }
    .orientation{
        width: 345px;
        text-align: center;
        position: absolute;
        left: 19%;
        bottom: -45%;
        h4{
            color:white;
            font-size:1rem;
            margin-bottom: 10px;
        }
        p{
            color: white;
        }
    }
    .demo{
        width: 345px;
        text-align: center;
        position: absolute;
        left: 34%;
        top: -51%;
        h4{
            color:white;
            font-size: 1rem;
            margin-bottom: 10px;
        }
        p{
            color: white;
        }
    }
    .evaluation{
        width: 345px;
        text-align: center;
        position: absolute;
        left: 50%;
        bottom: -45%;
        h4{
            color:white;
            font-size: 1rem;
            margin-bottom: 10px;
        }
        p{
            color: white;
        }
    }
    .graduation{
        width: 345px;
        text-align: center;
        position: absolute;
        left: 65%;
        top: -51%;
        h4{
            color:white;
            font-size: 1rem;
            margin-bottom: 10px;
        }
        p{
            color: white;
        }
    }
    .upcoming{
        width: 350px;
        margin: auto;
        font-size: 2.5rem;
        color: white;
        margin-bottom: 50px;
    }
    .events{
        width: 100%;
        height: 150px;
        justify-content: space-between;
        margin-bottom: 80px;
        .event{
            position: relative;
            width: calc(100%/3 - 20px);
            height: 100%;
            background-color: aliceblue;
            border-radius: 20px;
            text-align: center;
            padding: 25px 20px;
            h4{
                font-size: 1.7rem;
                margin-bottom: 5px;
            }
            small{
                color: #70727e;
                span{
                    margin-right: 10px;
                }
            }
            p{
                font-size: 0.9rem;
                color: #70727e;
                margin-bottom:14px;
            }
        }
    }
    .more button{
        padding: 10px 20px;
        position: absolute;
        right: calc(50% - 53.5px);
        border-radius: 30px;
        border: none;
        background-color: #e56768;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        color: white;
    }
    .view-all{
        text-align: center;
        button{
            padding: 18px 28px;
            background-color: #e9d758;
            color: white;
            border: none;
            border-radius: 30px;
        }
    }
</style>