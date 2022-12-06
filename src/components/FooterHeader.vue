<script>

</script>

<template>
    <section>
        <div class="subscribe row main-container">
            <h3>Subscribe Now to Our Newsletter!</h3>
            <div class="searchbar">
                <input type="text" placeholder="Email Adress">
                <div class="email-btn"><button><i class="fa-solid fa-paper-plane"></i></button></div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section{
        padding: 45px 0px;
        background-color: #e56768;
    }
    .subscribe{
        align-items: center;
        justify-content: space-between;
        h3{
            font-size: 2rem;
            color: white;
        }
        .searchbar{
            width: 35%;
            position: relative;
            input{
                height: 45px;
                border-radius: 30px;
                width: 100%;
                border: none;
                padding-left: 10px;
            }
            .email-btn{
                position: absolute;
                bottom: -6%;
                right: 0;
                button{
                    width: 50px;
                    height: 50px;
                    border-radius: 50%;
                    border: none;
                    background-color: #e9d758;
                    color: white;
                }
            }
        }
    }

</style>