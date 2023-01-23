<script>
import Card from './Card.vue';

export default{
    data(){
        return{
            
        }
    }
    ,
    components:{
        Card,
        
    }
}
</script>

<template>
    <div class="main-wrapper">
        <div class="top-main-wrapper">
            <div class="container">
                <Card/>
            </div>
        </div>
        <div class="bottom-main-wrapper">
            <div class="container">
                <div class="list-wrapper">
                    <ul>  
                        <h2>Titolo 1</h2>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>

                    </ul>
                    <ul>  
                        <h2>Titolo 2</h2>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>

                    </ul>
                    <ul>  
                        <h2>Titolo 3</h2>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>

                    </ul>
                    <ul>  
                        <h2>Titolo 4</h2>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>
                        <li>prova</li>

                    </ul>
                </div>
                <div class="img-wrapper">
                    <img src="./img/dc-logo-bg.png" alt="big dc logo">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.main-wrapper{
    .top-main-wrapper{
        background-color: black;
        min-height: 160px;
        .container{
            padding-top: 60px;
            h1{
                color: white;
            }
        }
    }
    .bottom-main-wrapper{
        height: calc(100% - 230px);
        background-image: url(./img/footer-bg.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        .container{
            display: flex;
            justify-content: space-between;
            .list-wrapper{
                display: flex;
                ul{
                    margin: 0 20px;
                    height: fit-content;
                }
                h2{
                    color: white;
                    margin-bottom: 0.9rem;
                }
                li{
                    color : rgb(161, 161, 161);
                    font-size: 0.8rem;
                }
            }
            .img-wrapper{
                height: 450px;
            }
            img{
                max-height: 100%;
            }
        }
    }
}
</style>