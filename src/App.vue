<template>
  <div id="app">
    <main>
    <div class="search-box">
      <input type="text" class="search-bar" placeholder="Zoeken...">

    </div>
    </main>
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
  
}
.search-box {
  width: 100%;
  margin-bottom: 29px;
}
.search-box .search-bar {
  display: block;
  width: 100%;
  padding: 15px;
  
  color: #313131;
  font-size: 20px;
  appearance: none;
  border:none;
  outline: none;
  background: none;
  box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.25);
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 0px 16px 0px 16px;
  transition: 0.4s;
}
.search-box .search-bar:focus{
  box-shadow:0px 0px 16px rgba(0, 0, 0, 0.25);
  background-color: rgba(255, 255, 255, 0.75);
  border-radius: 16px 0px 16px 0px;
}

</style>
