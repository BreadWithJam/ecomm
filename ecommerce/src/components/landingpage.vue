<script>


</script> 



<template>
<body class = "bg">
<div class = "container-fluid">
    <div class = "row align-items-center">
        <!--------------------------Navbar--------------------------------->
        
            <div class="con">
            <img src="C:\src\ecomm\ecommerce\src\assets\images\syapiLogo (1).png" alt="Logo" style="width: 180px; margin-right: 15px; height: 150px;">
                <input type="text" name="" id="" placeholder="Search" class="form-control rounded-pill shadow-sm"
                style=" width: 550px; height: 40px; margin-left: 170spx;">
               <button class = "btn searchbtn" style="margin-left: 30px; height: 40%; width: 5%; border-radius: 12px;"> 
                <i class="bi bi-search"> </i>
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
        <div class="container-fluid bcontainer mt-5">
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
                <img src="C:\src\ecomm\ecommerce\src\assets\images\banner4.png" alt="Women's wear'" style = "height: 300px; width: 700px; margin-top: 2%;">
                   </div>
            <div class="carousel-item" data-bs-interval="1500">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\banner5.png" alt="Shoes" style = "height: 300px; width: 700px; margin-top: 2%;">
                     <div class="carousel-caption" style="text-align: right">
                 </div>
                     </div>  

                 </div>
            </div>
            </div>
        

    <div class="col-5 mt-4">
        <div class="row">     
            <div class="col-3"><div class="glass-grid">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\shoes.png" alt="Women's wear">
            </div></div>
            <div class="col-3"><div class="glass-grid">1</div></div>
            <div class="col-3"><div class="glass-grid">1</div></div>
            <div class="col-3"><div class="glass-grid">1</div></div>

            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>


           <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>
            <div class="col-3"><div class="small-box glass-grid" style="background-color: blue;">1</div></div>


</div>
<div class="container" style="height: 94px;">
            
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
  align-items: center;
  width: 100%;
  height: 100px;       /* fixed height */
  padding: 15px 30px;
  position: fixed;    /* stick to top */
  top: 0;
  left: 0;
  z-index: 1000;
}

.con img{
    display:block;
    align-self: center;
    height: 100px;  
}

.glass-grid{
    background:rgba(0, 0, 0, 0.3);
    height: 90px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    color: #ffffff;
    font-weight: bold;
    border-radius: 10px;
    margin-top: 10px;
    overflow: hidden;
    align-items: center;
    display: flex;
    justify-content: center;
    position: relative;
}

.glass-grid img{
width: 100%;
height: 100%;
object-fit: cover;
border-radius: 15px;
}

.glass-grid::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.3); /* adjust darkness here */
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
}
</style>
