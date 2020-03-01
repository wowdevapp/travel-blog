<template>
  <div class="footer">
    <div class="container">
         <div class="row">
            <div class="col-md-4">
                 <ul class="list-unstyled contact">
                   <li class="logo">Travel Blog</li>
                   <li><i class="fas fa-phone" aria-hidden="true"></i>0123-456-789</li>
                   <li><i class="fas fa-envelope"></i>travel@gmail.com </li>
                   <li style="margin-top:20px" class="social">
                     <img style="width:40px;height:40px;margin-right:10px" src="../../assets/img/social/twitter.png" alt="">
                     <img style="width:40px;height:40px;margin-right:10px" src="../../assets/img/social/facebook.png" alt="">
                     <img style="width:40px;height:40px;margin-right:10px" src="../../assets/img/social/instagram.png" alt="">
                     <img style="width:40px;height:40px;margin-right:10px" src="../../assets/img/social/youtube.png" alt="">
                   </li>
                 </ul>
            </div>
            <div class="col-md-4">
                 <ul class="list-unstyled subscribe">
                   <li class="logo"><h3>Subscribe To Our Newsletter</h3></li>
                   <li class="" style="margin-bottom:20px"><p>Get the best content delivred straight into your box</p></li>
                   <li><div class="input-group">
                        <input type="text" class="form-control" placeholder="Your E-mail Adresse">
                        <span class="input-group-btn">
                          <button class="btn btn-default" type="submit">
                              <i class="fa fa-arrow-right"></i>
                          </button>
                        </span>
                      </div>
                  </li>
                 </ul>
            </div>
            <div class="col-md-4">
                 <ul style="margin-left:100px;padding-top:23px" class="list-unstyled menu">
                   <li class="active"> <a href=""> HOME</a></li>
                   <li class=""> <a href=""> BEST PLACES</a></li>
                   <li class=""> <a href=""> DESTINATIONS</a></li>
                   <li class=""> <a href=""> TRAVEL TIPS</a></li>
                   <li class=""> <a href=""> TRAVEL RESOURCES</a></li>
                 </ul>
            </div>
         </div>
    </div>
  </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@import '../../scss/variables';
.footer{
   margin: 0;
   padding:200px 0;
    min-height:500px;
    background-image: url('../../assets/img/footer/footer.jpg');
    background-size: cover;
    ul.contact{
      li{
        margin: 10px 0;
        i{
          margin-right:10px; 
        }
      }
      li.logo{
        margin: 20px 0;
        font-family: 'Leckerli One';
      }
    }
    ul.subscribe{
      li{
        margin: 10px 0;          
        }
        li.logo{
          h3{
            font-family: $heading;
          }
      }
      li .input-group input{
        background-color: transparent;
        border: 1px solid white;
        border-radius: 0;
      }
    }
    .menu li{
      margin-bottom:8px;  
    }
    .menu li.active{
        color: white;
        font-weight: bold;
      
    }
    }


</style>