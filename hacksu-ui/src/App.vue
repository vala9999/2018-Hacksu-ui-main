<template>
  <div id="app">
    <ul id="banner">
    <a href="https://khe.io" class="bannerItem" target="_blank">Kent Hack Enough</a>
    <a href="#" class="bannerItem">Contact</a>
    <a href="#" class="bannerItem">Constitution</a>
    <a href="#" class="bannerItem">FAQ</a>
  </ul>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
  
  html, body {
    margin: 0;
    padding: 0;
    max-width: 100vw;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}
  #banner {
  width: 100vw;
  position: fixed;
  background: black;
  z-index: 1000;
  display: flex;
  justify-content: flex-end;
  margin-top: 0;
  top: 0;
  margin-left: 0;

}
.bannerItem {
  color: white;
  transition-duration: .3s;
  height: 100%;
  display: inline-block;
  padding: 20px 20px;

}
.bannerItem:hover {
  background: #4683FF;

}
</style>
