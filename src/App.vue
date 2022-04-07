//HTML MAIN
<template>
    <div id="app">
        <Header/>
        <Main/>
        <SectionIcons/>
        <Footer/>
    </div>
</template>

//JS MAIN
<script>

// components
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import SectionIcons from './components/SectionIcons.vue'

//here we take an array of object from data
import dc_comics from '@/assets/data/dc-comics'

export default {
  name: 'App',

  data: function() {

    // we need an object so we put the data in the brackets
    return { dc_comics }
  },

  components: {
    Header,
    Main,
    Footer,
    SectionIcons
  }
}
</script>



/*********** CSS MAIN */
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
