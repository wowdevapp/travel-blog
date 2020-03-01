<template>
   <div class="videoPart">
       <div class="rectangle">
       </div>
      <div style="display:flex">
            <div class="video-centent">
            <iframe width="900" height="540" src="https://www.youtube.com/embed/Y7IoPLxJP1Y"
            frameborder="0"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen></iframe>
        </div>
        <div class="videos-control">
            <div class="control-1 active"><span style="margin-right:10px">Video 1</span><i class="far fa-play-circle"></i></div>
            <div class="control-1"><span style="margin-right:10px">Video 2</span><i class="far fa-play-circle"></i></div>
            <div class="control-1"><span style="margin-right:10px">Video 3</span><i class="far fa-play-circle"></i></div>
        </div>
      </div>
       <div style="display:block " class="video-parg">
           <i class="fas fa-quote-left"></i>
            <p>
                Nature last minute globe turkey hospitale get way <br>
                international tripits Paris Amsterdam nationale <br> earth flexibility
                bus diary tour operatour unsharted <br>
            </p>
       </div>

   </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@import '../../scss/variables';
.videoPart{
    position: relative;
    .video-content{
        width: 70%;
        z-index:9999 !important;
        position: relative;
    }
    .videos-control{
        width: 20%;
        .active{
            margin-left: 60px;
            position: relative;
            margin-bottom: 15px;
            margin-right: 15px;
            color: #000;

         &::after{
             content:"";
             width: 50px;
             position: absolute;
             top: 10px;
             left:-60px;
             border-top: 1px solid #000;  
        }
        }
        .control-1{
            margin-left: 60px;
            position: relative;
            margin-bottom: 15px;
            margin-right: 15px;

         &::after{
             content:"";
             width: 50px;
             position: absolute;
             top: 10px;
             left:-60px;
             border-top: 1px solid rgb(65, 64, 64);  
        }
        }

    }
    .rectangle{
        z-index: -1;
        position: absolute;
        width: 520px;
        height: 440px;
        background-color: rgb(234, 236, 237);
        top: 332px;
        right: 300px;
    }
    .video-parg{
        margin: 50px 0 0 50px;
        position: relative;
        p{
            position: absolute;
            top: 0;
            left: 10px;
            font-family: 'Cardo' ;
        }

    }
}



</style>