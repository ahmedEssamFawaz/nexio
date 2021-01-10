<template>
  <div class="container">
      <div class="row">
          <div class="col-md-6 col-sm-12">
              
              <img class="img-fluid"  alt="" :src="images.sample">
          </div>

           <div class="col-md-6 col-sm-12">
              <h3>See what’s new with up to 50% off online and in stores...</h3>
              <div class="desc">Shop the latest fashion online at Nicebeats and discover new favourites in women’s clothing. Find everything from casual day dresses to sharp office wear. We have jeans in every fit, premium quality items and the latest fashion essentials. Check out our Conscious collection made out of more sustainable materials, we bring you women’s fashion in a more sustainable way</div>
              <div class="read-more"><a href="#">Read more</a></div>
              
              <img class="img-fluid"  alt="" :src="images.sample2">
          </div>
      </div>

  </div>
</template>

<script>
export default {
    name: "SecondSection",
    data(){
        return{
            images: {
                sample: require('/public/img/hsty-img1.jpg'),
                sample2: require('/public/img/hsty-img2.jpg')
            }
        }
    }
}
</script>

<style scoped>

.container{
    margin: 90px auto;
}
   img{

        /* width: 558px; */
        /* height: 651px; */
        
        
    }
h3{
    text-align: start;
}
    .desc{
        display: inline-block;
        max-height: 352px;
        overflow: hidden;
        font-weight: 400;
        font-size: 16px;
        
        color: #979797;
        text-align: start;
        
    }
.read-more{
    text-align: start;
}
   a:link,
   a:visited {
       display: inline-block;
  text-decoration: none;
  color: #000;
  font-weight: 600;
  border-bottom: 2px solid;
  margin-bottom: 10px;
  text-align: start;
  padding: 8px 0;
  transition: color 0.25s,border-color 0.25s,background-color 0.25s,opacity 0.25s,width 0.25s ease 0s;
}
a:hover, a:focus, a:active {
    
    text-decoration: none;
    outline: none;
    color: #ff4040;
    
    
    
}


/************
1. 575px
************/

@media only screen and (max-width: 1024px)
{
     .desc{
        
        font-size: 10px;
 overflow-wrap: break-word;  
    }
		
   
}


</style>