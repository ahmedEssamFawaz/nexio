<template>
<header>
	<link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" 
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" 
        crossorigin="anonymous">

<nav class="navbar navbar-light navbar-expand-md bg-faded justify-content-center">
    
    <a href="/" class="navbar-brand d-flex w-50 mr-auto"><img src="https://nexio.famithemes.com/wp-content/themes/nexio/assets/images/logo-dark.svg" alt=""></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsingNavbar3">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="navbar-collapse collapse w-100" id="collapsingNavbar3">
        <ul class="navbar-nav w-100 justify-content-center">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="//codeply.com">shop</a>
                
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">elements</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#">blog</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#">pages</a>
            </li>
        </ul>
        <ul class="nav navbar-nav ml-auto w-100 justify-content-end">
            <li class="nav-item">
                <a class="nav-link" href="#">fb</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">in</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">pi</a>
            </li>
            
            
        </ul>
        &mdash;&mdash;&mdash;
    <div class="selectWrapper">
  <select class="selectBox">
        <img src="/img/tobias-Flag-of-the-United-Kingdom.svg" width="300" alt="" class="img-fluid">
  <option></option>
  
</select>
</div>
<div class="selectWrapper">
  <select class="selectBox">
       
  <option>GBG</option>
  
</select>
</div>

<div class="icons">
    <i class="fas fa-search"></i>
<i class="fas fa-user"></i>
<i class="fas fa-heart"></i>
</div>

    </div>
    

</nav>

        <Carasoul />    

</header>
    <!-- <div>
                <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
                    </div> 
        Hi
        
        </div> -->


</template>

<script>
import Carasoul from '../Carasoul'
export default {
    name: "Header",
    components: {
        Carasoul
    }
}
</script>

<style scoped>

.header{
    position: relative;
    
}
.navbar {
    position:absolute;
    top:30px;
    z-index:10;
    /* background:#fff; */
    width:100%;
   
}


.navbar-brand img {
    width: 70px;
    /* margin-left: 150px; */
   
}

.nav-link {
    color: black !important;
    text-transform: uppercase;
}

.selectWrapper{
  border-radius:36px;
  display:inline-block;
  overflow:hidden;
  background:#cccccc;
  border:1px solid #cccccc;
}
.selectBox{
  width:140px;
  height:40px;
  border:0px;
  outline:none;
}

.selectBox img{
    height: 130px;
    width: 150px;
}
.selectWrapper{
    margin-left: 10px;
}

.icons {
    display: flex;
    
}

.icons i {
    padding-right: 5px;
    padding-left: 5px;
}


@media only screen and (max-width: 767px)
{
    .navbar {
    position:absolute;
    top:0px;
    z-index:10;
    
    width:100%;
   
}

}
</style>