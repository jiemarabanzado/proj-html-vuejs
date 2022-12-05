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
            <h3>University year</h3>   
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
    </section>

</template>

<style lang="scss" scoped>
    section{
        background-color: #e56768;
        padding: 150px 0px;
        .time-section{
            height: 100%;
            h3{
                width: 306px;
                margin: auto;
                font-size: 2.9rem;
                background-color: #db2a2c;
                color: white;
                margin-bottom: 200px;
                
            }
        }

    }
    .bell{
        justify-content: center;
        margin-bottom: 20px;
    }
    .bell-img{
        width: 50px;
        img{
            width: 100%;
        }
    }
    .timeline{
        position: relative;
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
            font-size: 1.05rem;
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
            font-size: 1.05rem;
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
            font-size: 1.05rem;
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
            font-size: 1.05rem;
            margin-bottom: 10px;
        }
        p{
            color: white;
        }
    }
</style>