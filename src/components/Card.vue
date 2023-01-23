<script>
    export default{

    }
</script>
<template>
    <div class="card-wrapper">
        <div class="card">
             <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
             <p>comic name </p>
        </div>
        
    
    </div>
</template>


<style lang="scss" scoped>
.card-wrapper{
    display: flex;
    flex-wrap: wrap;
    .card{
        flex-basis: calc(100% / 6);
        margin-bottom: 2rem;
        height: 200px;
        img{
            width: 200px;
            object-fit: cover;
            object-position: top;
            padding: 0 10px;
          }
          p{
               color: white;
               padding: 0 10px;
               margin: 10px 0
          }
    }
}
</style>