<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

import store from 'src/store';

export default {
  store,
};
</script>

<style lang="scss">
  @import "./assets/scss/normalize.scss";
  body{
     background:
      radial-gradient(
        ellipse at center,
        rgba(51, 51, 51, 1) 0%,
        rgba(17, 17, 17, .75) 100%
      );
    /*   radial-gradient(
      ellipse at center,
      rgba(0, 0, 0, 1) 0%,
      rgba(7, 7, 7, .85) 100%
    ); */
    background-color: rgba(51, 51, 51, 1);
    background-position: center;
    font-family: -apple-system-, Helvetica, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-size: 13px;
    line-height: 1.5;

    #app {
      color: #fff;
    }
    .text-center{
      text-align: center;
    }
  }
  
</style>
