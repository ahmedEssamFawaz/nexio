<template>
  <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="\img\close.jpg" alt="First slide">
      <div class="title">
          <p class="main-title">Resi<span>parka</span></p>
      </div>
      <div  class="product_name_salary">
          <p class="side-title">Fine-knit Sweater</p>
          <span class="salary">23.99 USD</span>
          
      </div>
      <div class="shop-now">
          <button>Shop Now</button>
      </div>
      
      
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="/img/portrait.jpg" alt="Second slide">
       <div class="title">
          <p class="main-title">Resi<span>parka</span></p>
      </div>
      <div class="product_name_salary">
          <p class="side-title">Fine-knit Sweater</p>
          <span class="salary">23.99 USD</span>
          
      </div>
       <div class="shop-now">
          <button>Shop Now</button>
      </div>
    </div>
    
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
  
</template>

<script>
export default {
    name: "Carasoul"
}
</script>

<style scoped>

.carousel{
    /* position:absolute; */
    /* top:0; */
    
}

.carousel-item{
    position: relative;
}
.carousel-item .main-title{
    color: black;
    position: absolute;
    font-size: 140px;
    font-weight: 600;
    z-index: 10;
    top: 22%;
    left:22%;
    line-height: 200px;
    text-transform: uppercase;
}
.carousel-item .main-title span {
    position: absolute;
    top: 70%;
}
.product_name_salary{
    position: absolute;
    display: inline-block;
    top: 70%;
    left: 10%;
    /* z-index: 100; */
    border-left: 4px solid black;
}
.salary{
    font-weight: 500;
    padding-right: 70px;
    color: black;
}

.shop-now{
   position: absolute;
    top: 79%;
    left: 10%;
}

.shop-now button{
    
    
    text-transform: uppercase;
    z-index: 12;
    background-color: rgb(0, 0, 0);
    
    cursor: pointer;
    outline: none;
    box-shadow: none;
    
    color: rgb(255, 255, 255);
    text-decoration: none;
    /* white-space: nowrap; */
    width: 140px;
    height: 36px;
    min-height: 0px;
    min-width: 0px;
    max-height: none;
    max-width: none;
    text-align: center;
    line-height: 26px;
    letter-spacing: 2px;
    font-weight: 400;
    font-size: 13px;
    border-color: transparent;
    transform-origin: 77.5px 21px;
    opacity: 1;
    transform: translate(0px, 0px);
    visibility: visible;
    border-width: 0px;
    border-radius: 0px;
    border-style: none;
}
.shop-now button:hover,
.shop-now button:active{
    background-color: rgb(255, 64, 64);
}


.side-title{
    font-weight: 500;
    color: black;
    
    font-size: 120%;
    padding-left: 20px;
}

/************
1. 1100px
************/

@media only screen and (max-width: 1100px)
{
	
.carousel-item .main-title{
    
    font-size: 60px;
    
    top: 22%;
    left:12%;
    line-height: 150px;
    
}
.carousel-item .main-title span {
    
    top: 50%;
}
.product_name_salary{
    
    top: 70%;
    left: 10%;
    
  
}
.salary{
    padding-right: 80px;
    
}

.shop-now{
   
    top: 82%;
   
}



.side-title{
    
    
    
    font-size: 130%;
    padding-left: 20px;
}
}

/************
2. 768px
************/

@media only screen and (max-width: 768px)
{

		
   .carousel-item .main-title{
   
    font-size: 41px;
   
   
    top: 32%;
    left:17%;
    line-height: 70px;
    
}

.carousel-item .main-title span {
    
    top: 70%;
}

.product_name_salary{
    
    top: 67%;
    left: 10%;
    
}
.salary{
    padding-right: 65px;
  
    font-size: 120%;
    
}

.shop-now{
   position: absolute;
    top: 79%;
    left: 10%;
}

.shop-now button{
    
    width: 110px;
    height: 24px;
   
    
   
    
    font-size: 12px;
    
    margin-top: 26px;
}

.side-title{
    
  
    
    font-size: 120%;
    padding-left: 5px;
}
}

/************
3. 575px
************/

@media only screen and (max-width: 575px)
{
		
     
		
   .carousel-item .main-title{
   
    font-size: 28px;
   
   
    top: 22%;
    left:17%;
    line-height: 60px;
    
}

.carousel-item .main-title span {
    
    top: 60%;
}

.product_name_salary{
    
    top: 59%;
    left: 10%;
    
}
.salary{
    padding-right: 65px;
  
    font-size: 120%;
    
}

.shop-now{
   position: absolute;
    top: 75%;
    left: 10%;
}





    
}

/************
4. 479px
************/

@media only screen and (max-width: 479px)
{
     
   .carousel-item .main-title{
   
    font-size: 30px;
   
   
    top: 22%;
    left:12%;
    line-height: 50px;
    
}

.carousel-item .main-title span {
    
    top: 60%;
}

.product_name_salary{
    
    top: 59%;
    left: 10%;
    
}
.salary{
    padding-right: 65px;
  
    font-size: 100%;
    
}

.shop-now{
   position: absolute;
    top: 79%;
    left: 10%;
}



.side-title{
    
  
    
    font-size: 110%;
    padding-left: 5px;
}
   
}

/************
5. 396px
************/

@media only screen and (max-width: 396px)
{
   .carousel-item .main-title{
  
    font-size: 16px;
    font-weight: 600;
   
    top: 22%;
    left:17%;
    line-height: 70px;
    
}

.carousel-item .main-title span {
    
    top: 30%;
}

.product_name_salary{
    
    top: 59%;
    left: 10%;
   
    border-left: 2px solid black;
}
.salary{
    padding-right: 25px;
    
    font-size: 10px;
    
}

.shop-now{
   position: absolute;
    top: 73%;
    left: 10%;
}

.shop-now button{
    
   
   
    
    
    font-size: 10px;
    
   
    margin-top: 26px;
}

.side-title{
    
    
    font-size: 60%;
    padding-left: 5px;
}

}
</style>