<template>
  <div id="app">
    <Navbar/>
    <div>
      <router-view></router-view>
    </div>
    <Footer/>
  </div>
</template>


<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components:{
    Navbar,
    Footer
  }
}


</script>


<style>
*{
  margin: 0;
}
::-webkit-scrollbar {
  width: 12px;
  height: 12px;
}
::-webkit-scrollbar-track {
  background-color: #4b3f0f;
  border-radius: 10px;
}
::-webkit-scrollbar-thumb {
  background-color: #b4740e;
  border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
  background-color: #ee8738;
}
::-webkit-scrollbar-thumb {
  box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}


#app {
   font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #2c3e50;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 100vh;
    margin: 0;
}

</style>
