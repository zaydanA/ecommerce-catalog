<template>
  <div id="app">
    <div class="parentDiv">
      <h2 class="fakeCommerce">fakeCommerce</h2>
    </div>
    <CatalogView/>
    <!-- <WomenCatalog></WomenCatalog> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import CatalogView from './components/CatalogView.vue'
// import WomenCatalog from './components/WomenCatalog.vue'
// const isActive = true;

export default {
  name: 'App',
  components: {
      CatalogView,
      // WomenCatalog
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  min-height: 100vh;
  height: 100%;
  background: #ffffff;
  position: fixed;
  margin: 0;
  padding: 0;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  overflow-y: scroll;
  /* margin: auto; */
}

.fakeCommerce{
  position: absolute;
  left: 30px;
  top: 5px;
  z-index: 10;
  color: #ffffff;
  font-family: 'Trocchi', serif;
}
.parentDiv {
  position: relative;
  align-items: center;
  width: 100%;
  height: 80px;
  background-color: #070707;
  color: rgb(255, 255, 255);
}

</style>
