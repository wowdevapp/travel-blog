<template>
 <div class="section-five">
     <div class="container">
         <div class="col-md-6">
            <div class="img-5">
               <img src="../../assets/img/five-sec/easy.jpg" alt="">
            </div>
         </div>
         <div class="col-md-6 head-par">
            <h2>Easy Ways To make Travel <br>Faster</h2>
            <p>
                Europe nationale globe hotspots hikings miles sleep <br> turkey
                international tripits Paris Amsterdam nationale <br> earth flexibility
                bus diary tour operatour unsharted <br> mass Europe guide flequent flyer
                yasht miles <br>  charting miles <br><br>
                Europe nationale globe hotspots hikings miles sleep <br>
                turkey
                international tripits
            </p>
            <div style="padding-top:30px ;font-size:1rem;color:#000" href=""> <a href="" style="color:#000">READ MORE</a>  <i style="margin-left:10px" class="fas fa-arrow-right 2x"></i></div> 
         </div>
     </div>
     <!------------------------
     part two
     -------------------------->

          <div class="container part-2-5">
                <div class="col-md-6 head-par-2">
                    <h2>The travel meastrey revealed.</h2>
                    <p>
                        Europe nationale globe hotspots hikings miles sleep <br> turkey
                        international tripits Paris Amsterdam nationale <br> earth flexibility
                        bus diary tour operatour 
                    </p>
                    <div style="padding-top:30px ;font-size:1rem;color:#000" href=""> <a href="" style="color:#000">READ MORE</a>  <i style="margin-left:10px" class="fas fa-arrow-right 2x"></i></div> 
                </div>
                <div class="col-md-6 revealed">
                    <div class="img-5-two">
                      <img src="../../assets/img/five-sec/revealed.jpg" alt="">
                    </div>
                </div>
           </div>
           <div style="min-height:140px" class="travel-back">

           </div>
 </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@import '../../scss/variables';
.section-five{
    position:relative;
    .img-5{
        position: absolute;
        top: 50px;
        left: 18px;
        -webkit-box-shadow: -180px -100px 0px 0px rgba(0, 0, 0, 0.31);
        box-shadow: -188px -50px 0px 0px rgba(0, 0, 0, 0.1)
    }
    .head-par{
        padding-top: 60px;
        padding-left: 20px;
        h2{
            font-family: $heading;
            color: #000;
            font-weight:500;
            padding-bottom: 20px;

        }
    }
    .part-2-5{
        position: relative; 
        padding-bottom:100px;
        .head-par-2{
            padding-top:20rem;
            h2{
                color: #000;
                font-family: $heading;
                padding-bottom:20px; 

            }
        }
        .revealed{
            position: relative;           
            .img-5-two{
                position: absolute;
                top: 8rem;
                left: 22px;
                -webkit-box-shadow: 84px 63px 0px 0px rgba(0,0,0,0.1);
                -moz-box-shadow: 84px 63px 0px 0px rgba(0,0,0,0.1);
                box-shadow: 84px 63px 0px 0px rgba(0,0,0,0.1);
            }
        }
      
    }
    .travel-back{
        background-image: url('../../assets/img/five-sec/travel-back.jpg');
        background-repeat: no-repeat;
        background-position: bottom left;
    }
} 

</style>