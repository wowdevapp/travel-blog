<template>
   <div class="section-four">
       <div class="container">
           <div class="row">
               <div class="col-md-4 heading-parg">
                   <h2>Tips for Traveling in <br> Winter Season</h2>
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
               <div class="col-md-4 text-center img-1">
                   <img src="../../assets/img/four-sec/wintr.jpg" alt="" srcset="">
               </div>
               <div class="col-md-4 img-2">
                  <div class="div-floot"><img src="../../assets/img/four-sec/img-2.jpg" alt="" srcset=""></div>   
               </div>
           </div>
       </div>
<!---------------------
part two of section four
----------------------->
       <div class="background text-center">
            <h2 style="font-family:$heading" class="text-center">
                Adventure & Action in Travel
            </h2>
       </div>
   </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@import '../../scss/variables';
.section-four{
    .heading-parg{
        padding-top: 150px;
        h2{
            font-family: $heading;
            color: #000;
            font-weight: bold;
            padding-bottom: 30px;
        }
    }
    .img-1{
        padding-top: 145px;
    }
    .img-2
         {
           position: relative;
           .div-floot{
               position: absolute;
               top: 0;
               right: 0;
               -webkit-box-shadow: 30px 30px 0px 0px rgba(0,0,0,0.31);
               -moz-box-shadow: 30px 30px 0px 0px rgba(0,0,0,0.31);
               box-shadow: 30px 30px 0px 0px rgba(0,0,0,0.31);
           }
          }
/*---------------------
part two of setcion four
------------------------*/
    .background{
        background-image: url('../../assets/img/four-sec/background-2.jpg');
        min-height: 300px;
        background-repeat: no-repeat;
        background-size:cover;
        position: relative;
        h2{ 
            position: absolute;
            top: 50%;
            width: 100%;
            font-family:$heading;
            color: #000;
        }
    }
} 

</style>