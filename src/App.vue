<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  data(){
    return{

    }
  }
  ,
  components:{
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  
</template>

<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}
/*generics */ 
ul{
  list-style-type: none;
}
img{
  max-height: 100%;
  width: auto;
}
</style>
