<template>
  <div id="app">
    <header>
    <ul id="banner">
      <a href="https://khe.io" class="bannerItem" target="_blank">
        Kent Hack Enough
      </a>
      <a href="#" class="bannerItem">
        Contact
      </a>
      <a href="#" class="bannerItem">
        Constitution
      </a>
      <a href="#" class="bannerItem">
        FAQ
      </a>
      <a href="#" class="bannerItem">
        Login/Register
      </a>
    </ul>
    </header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
  
header {
  display: flex;
  justify-content: flex-end;

  width: 100%;
  max-width: 1440px;
}

header li {
  display: inline-block;
  padding: 20px 20px;

  font-family: 'Abel', sans-serif;
}
  
#banner {
  width: 100%;
  position: fixed;
  background: #041017;
  z-index: 1000;
  display: flex;
  justify-content: flex-end;
  margin-top: 0px;
  top: 0px;
  margin-right: 0px;
  right: 0px;


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
  
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
