<script>


</script> 



<template>
<body class = "bg">
<div class = "container-fluid">
    <div class = "row align-items-center">
        <!--------------------------Navbar--------------------------------->
        
            <div class="con">
            <img src="C:\src\ecomm\ecommerce\src\assets\images\syapiLogo (1).png" alt="Logo" style="width: 180px; margin-right: 15px;">
                <input type="text" name="" id="" placeholder="Search" class="form-control rounded-pill shadow-sm"
                style=" width: 550px; height: 40px; margin-left: 170spx;">
               <button class = "btn searchbtn" style="margin-left: 30px; height: 40%; width: 5%; border-radius: 12px;"> 
                <i class="bi bi-search" style="margin-bottom: 50px;"> </i>
               </button>
               <div style="margin-left: 8%; margin-right: 0;">
                <button class="iconbtn" style="margin-right: 30px;">
                <i class="bi bi-cart-plus fs-4"></i>
                </button>
                <button class="ls-btn" style="font-size: 18px;"> Login </button>
               <button class="ls-btn" style="margin-left: 18px;">Sign Up</button>
               </div>
            
        </div> 
            </div>
                </div>
                   
                    <!----------------------------Carousel-------------------------->
        <div class="container-fluid bcontainer mt-4">
            <div class="row">
                 <div class="col-7 mt-3">
                    <div id = "carouselContent" class = "carousel slide" data-bs-ride = "carousel">
                        <div class="carousel-inner">
                          <div class="carousel-item active" data-bs-interval = "1500">
                        <img src="C:\src\ecomm\ecommerce\src\assets\images\saleBanner.png" alt="bags" style = "height: 300px; width: 100%; margin-top: 2%;">
                            <div class="carousel-caption" style="text-align: right;">
                         </div>
                    </div>
                
                  
                <div class = "carousel-item" data-bs-interval="1100">
                        <img src="C:\src\ecomm\ecommerce\src\assets\images\banner2.png" alt="sandals" style = "height: 300px; width: 100%; margin-top: 2%;">
                        <div class="carousel-caption" style="text-align: right;"></div>
                </div>
        
       
            <div class="carousel-item" data-bs-interval="1500">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\womensWear.png" alt="Women's wear'" style = "height: 300px; width: 200px; margin-top: 2%;">
                   </div>
            <div class="carousel-item" data-bs-interval="1500">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\Shoes.png" alt="Shoes" style = "height: 300px; width: 350px; margin-top: 2%;">
                     <div class="carousel-caption" style="text-align: right">
                 </div>
                     </div>  

                 </div>
            </div>
            </div>
        

    <div class="col-5 d-flex align-items-center mt-4">
        <div class="row">
        <div class="container mb-1" style="background-color: red; height: 90px;">     
            <img src="C:\src\ecomm\ecommerce\src\assets\images\banner3.png" alt="" style="height: 150px; width: 50%;">           
</div>
<div class="container" style="background-color: blue; height: 94px;">
            <h2 style="font-size: 35px; font-weight: bold;"> 
                Only at Syapi.
            </h2>
        </div>
    </div>
    </div>
    
    <div class="container-fluid mt-4">
    <div class="col-12" style="background-color: #FFD54F;">
    </div>
</div>

    </div>  
        </div>


</body>
</template>



<style>
 .searchbtn{
    background-color: #0a0a0a !important; 
    color: #ffffff !important;
 }

 .ls-btn{
    background-color: transparent;
    color: #333333;
    border-radius: 8px;
 }
 
 .ls-btn:hover{
    border-color: #0a0a0a;
 }

 .iconbtn{
     background-color: transparent;
    color: #333333;
    height: 50px;
    width: 55px;
 }

 .iconbtn:hover{
    border-color:transparent;
 }

.bcontainer{
    
    background-color: #FFFFFF;
    width: 100%;
    min-height: 100vh;
    border-radius: 20px;
    padding: 20px;
}

container{
    width: 100%;
}

.colTagline{
    background-color: #F47C68;
    color: white;
    border-radius: 10px;
   padding: 50px 20px;
   max-width: 500px;
}

.con{
  background-color: #FFF0ED; /* full navbar color */
  display: flex;
  align-items: flex-start;
  width: 100%;
  height: 130px;       /* fixed height */
  padding: 15px 30px;
  position: fixed;    /* stick to top */
  top: 0;
  left: 0;
  z-index: 1000;
}

.con img{
    display:block;
    align-self: flex-start;
    height: 100px;  
}
</style>
