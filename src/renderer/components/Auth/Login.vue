<template>
<div class="container" style="height:100%;">
aad
<vue-particles
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
</div>
</template>

<script>
  export default {
    name: 'login',
    methods: {}
  }
</script>

<style>

  body {
    background: #BBD2C5;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #292E49, #536976, #BBD2C5);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #292E49, #536976, #BBD2C5); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  }
</style>
