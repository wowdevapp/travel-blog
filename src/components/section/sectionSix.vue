<template>
<div>
<!-------------------
part 1 section six
---------------------->
    <div class="section-six">
        <div class="content text-center">
            <h2 class="text-center"><i class="fas fa-quote-left"></i></h2>
            <p>
                "We're a bold bunch of reader's explorers&<br>
                hard core thrill that bring it''.
            </p>
        </div>
   </div>
<!-------------------
part 2 section six
---------------------->
<div class="part-2-6">
   <div class="container">
       <div style="position:relative" class="col-md-6">
           <div class="image-cont">
               <img src="../../assets/img/sec-six/man-travel.jpg" alt="">
           </div>
       </div>
       <div  class="col-md-6">
           <div class="backg-container">
              <img src="../../assets/img/sec-six/travel.jpg" alt="">
           </div>
       </div>
   </div>
</div>
<!-------------------
part 3 section six
---------------------->
<div class="part-3-6">
   <div class="container">
       <div class="col-md-6">
           <div class="parag-cont">
            <h2>Guide To Drive in Hill <br>Station</h2>
            <p>
                Europe nationale globe hotspots hikings miles sleep <br> turkey
                international tripits Paris Amsterdam nationale <br> earth flexibility
                bus diary tour operatour unsharted <br> mass Europe guide flequent flyer
                yasht miles
            </p>
            <div style="padding-top:30px ;font-size:1rem;color:#000" href=""> <a href="" style="color:#000">READ MORE</a>  <i style="margin-left:10px" class="fas fa-arrow-right 2x"></i></div>
           </div>
       </div>
       <div  class="col-md-6" style="position:relative">
           <div class="img-container">
              <img src="../../assets/img/sec-six/hikn.jpg" alt="">
           </div>
       </div>
   </div>
</div>
<!-------------------
part 4 section six
---------------------->
<div class="lastback">

</div>

</div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@import '../../scss/variables';
/*--------------------
part 1 section six
----------------------*/
.section-six{
    min-height: 350px;
    margin-top: 150px;
    background-image: url("../../assets/img/sec-six/background.jpg");
    background-repeat: no-repeat;
    position: relative;
    .content{
        position: absolute;
        top: 30%;
        width: 100%;
        font-size: 3rem;
        p{
             font-size: 3rem;
             font-family: $heading;
             color: #000;
        }
    }
    
}
/*--------------------
part 2 section six
----------------------*/
.part-2-6{
    position: relative;
    .image-cont{
        position: absolute;
        top: 0;
        right:0px;
        width: 285px;
        -webkit-box-shadow: -33px 32px 5px 0px rgba(0,0,0,0.32);
        -moz-box-shadow: -33px 32px 5px 0px rgba(0,0,0,0.32);
        box-shadow: -33px 32px 5px 0px rgba(0,0,0,0.32);
    }
    .backg-container{
        position: absolute;
        top: 0;
        right: -169px;
    }
}
/*--------------------
part 3 section six
----------------------*/
.part-3-6{
    padding:100px 0;
    .parag-cont{
       margin-top: 40rem;
       h2{
           font-family: $heading;
           color: #000;
           margin-bottom: 20px;
       }
    }
    .img-container{
        position: absolute;
        left: 85px;
        top: 0;
    }
}
/*--------------------
part 4 section six
----------------------*/
.lastback{
    min-height: 120px;
    background-image: url('../../assets/img/sec-six/Lastback.jpg')
}

</style>