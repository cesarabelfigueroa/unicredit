<template>
  <div id="app">
    <Header/>

    <div class="container"> 
      <div id="header-content">
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}



#header-content{
  width: 100%;
  height: 100vh;
  position: relative;
  background: #f5f8fd url(./assets/intro-bg.jpg) center top no-repeat;
  background-size: cover;
}
</style>


<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  name: "App",
  components: {
    Header
  }
};


</script>
