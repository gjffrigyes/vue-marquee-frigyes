<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<router-view>sadf</router-view>-->
    <div class="marquee-wrap"><vueMarquee content="222222222" class="two"  showtwo="false"></vueMarquee></div>
    <div class="marquee-wrap"><vueMarquee content="111111111" class="two"  showtwo="false"></vueMarquee></div>
    <div class="marquee-wrap"><vueMarquee content="3" class="two"  :showtwo="false" speed="quick" ></vueMarquee></div>
  </div>
</template>

<script>
  // import Hello from './components/Hello'
  import vueMarquee from './Marquee.vue'

  export default {
    name: 'app',
    components: {
      vueMarquee
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    height:80px;
    background: #858585;
  }
  .marquee-wrap {
    width: 100px;
    margin: 0 auto;
  }
</style>
