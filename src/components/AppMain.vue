<script>
import Card from './Card.vue';

export default{
    data(){
        return{
            ComicsList:[
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
                price: '$19.99',
                series: 'Action Comics',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
                price: '$3.99',
                series: 'American Vampire 1976',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
                price: '$16.99',
                series: 'Aquaman',
                type: 'graphic novel',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
                price: '$2.99',
                series: 'Batgirl',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
                price: '$3.99',
                series: 'Batman',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
                price: '$2.99',
                series: 'Batman Beyond',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
                price: '$3.99',
                series: 'Batman/Superman',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
                price: '$4.99',
                series: 'Batman/Superman Annual',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
                price: '$5.99',
                series: 'Batman: The Joker War Zone',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
                price: '$6.99',
                series: 'Batman: Three Jokers',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
                price: '$4.99',
                series: 'Batman: White Knight Presents: Harley Quinn',
                type: 'comic book',
            },
            {
                thumb:
                'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq',
                price: '$16.99',
                series: 'Catwoman',
                type: 'graphic novel',
            },
            ]
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
            <a href="#">Current Siries</a>
            <div class="container">
                <Card v-for="comic in ComicsList" :comic="comic"  :key="comic.series"/>
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
@use './sass/colors.scss' as *;
.main-wrapper{
    .top-main-wrapper{
        background-color: black;
        min-height: 160px;
        padding-bottom: 50px;
        .container{
            display: flex;
            flex-wrap: wrap;
            padding-top: 60px;
        }
        a{
            padding: 15px;
            color: white;
            background-color: $main-blue;
            font-size: 23px;
            position: relative;
            left: 250px;
            top: -15px;
            transition:  0.5s linear;
            &:hover{
                box-shadow: lightgray 10px 10px;
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