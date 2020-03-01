<template>
   <div class="section-three">
        <h1 class="rotated">
            What do you think <br> of travelling
        </h1>
        <div class="container">
            <div class="row">
                <div class="col-md-6 text-center">
                   <div class="three-img">

                   </div>
                </div>
                <div class="col-md-6 parag">
                   <h1>An amazing <br> Journey Through <br> the montains</h1>
                   <p>
                       Europe nationale globe hotspots hikings <br> miles sleep turkey international
                        tripits Paris <br> Amsterdam nationale earth flexibility bus <br> diary tour
                         operatour unsharted maps <br> Europe guide flequent flyer yasht miles <br>
                        charting the China country 
                   </p>
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
.section-three{
position: relative;
padding-top:100px;
h1.rotated{
    position: absolute;
    font-family: $heading;
    top: 0;
    right:-100px;
    color: #000;
    transform: rotate(-270deg);
    transform-origin: 0 0;
    &::after{
        content: "";
        width: 100px;
        position: absolute;
        top: 60px;
        right: 0;
        border-top: 2px solid #000;
    }
}
h1{
    font-family: $heading;
    color: #000;
}
.parag{
    padding: 0  10rem 0 0;
}
.three-img{
    width: 400px;
    height: 400px;
    background-color: #000;
    background-image: url("../../assets/img/three-sec/italy.jpg");
    background-size: cover;
}
}
</style>