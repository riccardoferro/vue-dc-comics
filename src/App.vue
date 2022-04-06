//HTML MAIN
<template>
    <div id="app">
        <Header/>
        <Main/>
        <Footer/>
    </div>
</template>

//JS MAIN
<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

//CSS MAIN
<style lang="scss">

//general settings

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container70 {
  width: 70%;
  margin: 0 auto;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color:black;
  height: 100vh;
  width: 100vw;
}

</style>
