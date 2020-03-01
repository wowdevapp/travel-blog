<template>
  <div id="app">
     <appHeader></appHeader>
     <sectionTwo></sectionTwo>
     <sectionThree></sectionThree>
     <sectionFour></sectionFour>
     <sectionFive></sectionFive>
     <videoPart></videoPart>
     <sectionSix></sectionSix>
     <foot></foot>
  </div>
</template>

<script>
import sectionTwo   from "./components/section/sectionTwo.vue";
import sectionThree from "./components/section/sectionThree.vue";
import sectionFour  from "./components/section/sectionFour.vue";
import sectionFive  from "./components/section/sectionFive.vue";
import videoPart    from "./components/section/videoPart.vue"; 
import sectionSix   from "./components/section/sectionSix.vue"; 
import foot       from "./components/section/foot.vue"; 
export default {
  name: 'App',
  components: {
     'sectionTwo'  : sectionTwo,
     'sectionThree': sectionThree,
     'sectionFour' : sectionFour,
     'sectionFive' : sectionFive,
     'videoPart'   : videoPart,
     'sectionSix'  : sectionSix,
     'foot'      : foot,
  }
}
</script>

<style lang="scss">
@import 'scss/variables';
#app {
 color:$main-color
}
p{
  font-family: $paragraphs;
  color:$main-color;
}
a{
  color:$main-color;
}
</style>
