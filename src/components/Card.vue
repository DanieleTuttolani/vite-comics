<script>
    export default{
     props:{
         comic: Object
     }
    }
</script>
<template>
        <div class="card">
             <img :src="comic.thumb" :alt="comic.series">
             <p>{{ comic.series }}</p>
        </div>
</template>


<style lang="scss" scoped>

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

</style>