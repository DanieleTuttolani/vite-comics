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
            }
        }
        .right{
            display: flex;
            h2{
                color: $main-blue;
            }
        }
    }
}
</style>