<template>
  <div>
    <site-header></site-header>
      <lottie-animation
      path='./70662-olympics-run-animation-tokyo-2021.json'
      :loop="false"
      :autoPlay="true"
      :loopDelayMin="2.5"
      :loopDelayMax="5"
      :speed="1"
      :width="256"
      :height="256"
      @AnimControl="setAnimController"
  />
    <site-footer></site-footer>
  </div>
</template>

<script>
import LottieAnimation from 'lottie-vuejs' // import lottie-vuejs

export default {
  components: {
      LottieAnimation
  },
  data: () => ({
    
  })
};
</script>