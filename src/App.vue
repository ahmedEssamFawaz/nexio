<template>
  <div id="app">
    <Header />
    <Home />
    <!-- <router-view/> -->
  </div>
</template>


<script>
import Header from './components/layout/Header'
import Home from './views/Home'
export default {
  name:'App',
  components:{
    Header,
    Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Montserrat, Arial, sans-serif;
  font-size: 16px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  /* padding: 30px; */
}

#nav a {
  /* font-weight: bold; */
  /* color: #2c3e50; */
}

#nav a.router-link-exact-active {
  /* color: #42b983; */
}
</style>
