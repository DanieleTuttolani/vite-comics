<script>


export default{
    data(){
        return{
            Navlinks:[
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
            ]
        }
    }
}

</script>

<template>
    <div class="nav-wrapper">
        <div class="container">
            <nav>
                <div class="main-nav-logo">
                    <img src="./img/dc-logo.png" alt="dc logo">
                </div>
                <div class="nav-list">
                    <ul>
                        <li v-for="link in Navlinks" :key="link-text">
                            <a :href="link.url">{{ link.text }}</a>
                        </li>
                        
                    </ul>
                </div>
            </nav>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use './sass/mixin/justify_align_center.scss' as *;
@use './sass/colors.scss' as *;

.nav-wrapper{
    height: 160px;
    nav{
        display: flex;
        justify-content: space-between;
        height: 160px;
        .main-nav-logo{
            @include justify_align_center;
        }
        .nav-list{
            @include justify_align_center;
        }
        ul{
            display: flex;
            li{
                padding: 0;
                margin: 0 0.6rem;
                a{
                    padding: 50% 8px;
                    &:hover{
                        color: $main-blue;
                    }
                }
            }
        }
    }
}
</style>