<script>
export default{
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="footer-wrapper">
                <div class="left">
                    <a href="#"> SING UP NOW! </a>
                </div>
                <div class="right">
                    <H2>FOLLOW US</H2>
                    <img src="./img/footer-facebook.png" alt="facebook dc">
                    <img src="./img/footer-periscope.png" alt="periscope dc">
                    <img src="./img/footer-pinterest.png" alt="pinterest dc">
                    <img src="./img/footer-twitter.png" alt="twitter dc">
                    <img src="./img/footer-youtube.png" alt="youtube dc">

                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use './sass/colors.scss' as *;
footer{
    background-color: #303030;
    height: 180px;
    .footer-wrapper{
        display: flex;
        justify-content: space-between;
        padding-top: 75px;
        .left{
            a{
                border: 2px solid $main-blue;
                color: white;
                padding: 20px;
                &:hover{
                    border-color: white;
                    cursor: pointer;
                }
            }
        }
        .right{
            display: flex;
            h2{
                color: $main-blue;
                margin: 0 0.5rem;
                &:hover{
                    color: white;
                    cursor: pointer;
                }
            }
            img{
                margin: 0 0.5rem;
                cursor: pointer;
            }
        }
    }
}
</style>