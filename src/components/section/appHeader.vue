<template>
<header> 
<!-------------------------------------
start navbar
-------------------------------------->
<div class="main-head">
    <nav class="navbar">
        <div class="container">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#">Travel Blog</a>
          </div>
          <div class="collapse navbar-collapse" id="navbar-collapse">
          <ul class="nav navbar-nav navbar-right">
            <li><a href="" class="active">HOME</a></li>
            <li><a href="">BEST PLACES</a></li>
            <li><a href="">DESTINATION</a></li>
            <li><a href="">TRAVEL TIPS</a></li>
            <li><a href="">TRAVEL RESOURCES</a></li>
          </ul>
          </div>
        </div>
    </nav>
<!----------------------------------------
end navbar
------------------------------------------>
    <div class="head">
       <div class="img-content">
          <div class="hbox">
              <h3>Why you should go for a trip...<i style="font-size:10px" class="fas fa-plane fa-xs"></i></h3>
              <h1>Traveling is Easier. <br>
                  than You think</h1>
              <span>
                <a href="">READ MORE <img style="width:30px" src="../../assets/img/header/row.png" alt="" srcset=""> </a>
              </span>
          </div>
       </div>
    </div>  
<!----------------------------------------
start carousel
------------------------------------------>
<div class="main-carousel">
  <div class="carousel-cell"><img src="../../assets/img/carousel/1.jpg" alt="" srcset=""></div>
  <div class="carousel-cell"><img src="../../assets/img/carousel/2.jpg" alt="" srcset=""></div>
  <div class="carousel-cell"><img src="../../assets/img/carousel/3.jpg" alt="" srcset=""></div>
  <div class="carousel-cell"><img src="../../assets/img/carousel/1.jpg" alt="" srcset=""></div>
  <div class="carousel-cell"><img src="../../assets/img/carousel/2.jpg" alt="" srcset=""></div>
</div>
<div class="buttons text-center">
     <span><img src="../../assets/img/header/arrow-left.png" alt="" srcset=""></span>
     <span><img src="../../assets/img/header/arrow-right.png" alt="" srcset=""></span>
</div>
</div>
</header>
</template>
<script>
export default {
  
}
</script>
<style lang="scss">
@import '../../scss/variables';
/*----------------------------------
Start Navbar Styling
------------------------------------*/ 
.navbar{
  background-color: white;
  margin-bottom: 0;
  .navbar-brand{
  font-family: 'Leckerli One';
  font-weight:400;
  }
  .navbar-nav a{
   font-weight:bold;
   font-size: 12px;
   font-family: $paragraphs
  }
  .navbar-nav a.active::after{
    content: "";
    position: absolute;
    width: 34px;
    border-top: 2px solid $main-color;
    top : 28px;
    left : 16px;
}
}
/*----------------------------------
Start Main-Head
------------------------------------*/ 
.main-head{
  height:100vh;
  position: relative;
  .img-content{
    width: 78%;
    height:80vh;
    background-color: black;
    background-image: url('../../assets/img/header/travel.jpg');
    background-size:100%;
    position: relative;
    color: white;
    .hbox{
        width: 460px;
        height: 279px;
        background-color: #4b4b4b;
        position: absolute;
        top: 10rem;
        right: -14rem;
        padding: 45px 40px;
        h1{
          font-family:$heading;
          font-weight: 400;
          margin-bottom: 40px;
        }
        span{
          margin-top: 30px;
          a{
            color:white;
            font-size: 10px;
          }
        }
    }


  }
  /*---------------------carousel---------------
  ----------------------------------------------*/
      .main-carousel{
         position: absolute;
         bottom: 0;
         right: 0;
         z-index: 100;
         width: 47%;
        .carousel-cell {
          width: 35%; /* half-width */
          height: 160px;
          margin-right:10px;
      }
}
      .buttons{
        width:80%;
        padding: 4rem 0;

      }

}
/*----------------------------------
end Main-Head
------------------------------------*/ 



</style>