<template>
  <div id="app">
    <div class="search-box">
      <input type="text" class="search-bar" placeholder="Zoeken...">

    </div>
  </div>
</template>
<script>
export default {
  name: 'app',
  data () {
    return {
      api_key: '5901b71ee509629f421b590fbf5eb5a2'
      
    }
  }

}
</script>



<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

body{
    font-family:'arial';

}
#app{
  background-image:url('./assets/summerbackground.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}
main{
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom,);
  
}
</style>
