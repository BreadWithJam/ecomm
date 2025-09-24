<script>


</script> 



<template>
    <body class = "bg">
<div class = "container-fluid">
    <div class = "row align-items-center">
        <div class = "col-lg-12 d-flex align-items-center"style = "height: 50px">
           
            <img src="C:\src\ecomm\ecommerce\src\assets\images\syapiLogo (1).png" alt="Logo" style="width: 180px; height: 200px; margin-right: 15px;">
                <input type="text" name="" id="" placeholder="Search" class="form-control rounded-pill shadow-sm"
                style=" width: 550px; height: 40px; margin-left: 170spx;">
               <button class = "btn searchbtn" style="margin-left: 30px; height: 65%; width: 5%; border-radius: 12px;"> 
                <i class="bi bi-search"> </i>
               </button>
               <div style="margin-left: 17%; margin-right: 0;">
                <button class="ls-btn"> Login </button>
               <button class="ls-btn" style="margin-left: 10px;">Sign Up</button>
               </div>
            
        </div> 
</div>
 </div>
        <div class="container-fluid bcontainer mt-4">
            <div class="row">
        <div class="col-7">
            <div id = "carouselContent" class = "carousel slide" data-bs-ride = "carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval = "1500">
                        <img src="C:\src\ecomm\ecommerce\src\assets\images\bags.png" alt="bags" style = "height: 200px; width: 350px; margin-top: 2%;">
                        <div class="carousel-caption" style="text-align: right;"></div>
                    </div>
                </div>
                  
                <div class = "carousel-item" data-bs-interval="1100">
                        <img src="C:\src\ecomm\ecommerce\src\assets\images\sandals.png" alt="sandals" style = "height: 200px; width: 350px; margin-top: 2%;">
                        <div class="carousel-caption" style="text-align: right;"></div>
                </div>
            </div>
       
            <div class="carousel-item" data-bs-interval="1100">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\womensWear.png" alt="Women's wear'" style = "height: 200px; width: 350px; margin-top: 2%;">
                    <div class="carousel-caption" style="text-align: right">
                    </div>
                     </div>

            <div class="carousel-item" data-bs-interval="1100">
                <img src="C:\src\ecomm\ecommerce\src\assets\images\Shoes.png" alt="Shoes" style = "height: 200px; width: 350px; margin-top: 2%;">
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
</style>
