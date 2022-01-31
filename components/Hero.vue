<template>
 <div>
      <div v-rellax="{
      speed: -6,
      zindex: 10
      }" class="layer-one">
      I'm a slow and smooth
    </div>
    <div v-rellax="{
      speed: 10,
      zindex: 5
      }" class="layer-two">
      I'm a slow and smooth
    </div>
 </div>
    <!--
     <div class="container is-fullhd">
    <section>
      <div class="is-flex is-flex-direction-column is-align-items-center first-title">
        <h1 class="title is-1">
          Title 1
        </h1>
        <h3 class="subtitle is-3">
          Subtitle 3
        </h3>
      </div>
      <div class="is-flex is-flex-direction-column is-align-items-center second-title">
        <h2 class="title is-2">
          Title 2
        </h2>
        <h4 class="subtitle is-4">
          Subtitle 4
        </h4>
      </div>
    </section>
  </div>
  -->
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
  .first-title {
    margin-top: 4rem;
  }
  .second-title {
    margin-top: 6rem;
  }
  .layer-one {
    height: 500px;
    background-image: url("https://e1.pngegg.com/pngimages/298/527/png-clipart-snoopy.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .layer-two{ 
    height: 500px;
    background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRtNFMPhuk4WeILtAU_8O6wiWJy2q67BX8AOg&usqp=CAU");
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>