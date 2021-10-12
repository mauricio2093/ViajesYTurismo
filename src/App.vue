<template>
    <v-app>
      <Barnav/>
      <v-main>
        <Home/>
        <About/>
        <Experience/>
        <Video/>
        <Place/>
        <Hotel/>
        <Subcribe/>
        <Sponsor/>
      </v-main>
      <Footer/>
      <Scroll/>
    </v-app>
</template>

<script>
import Barnav from './components/Barnav.vue'
import Home from './components/Home.vue'
import Experience from './components/Experience.vue'
import Video from './components/Video.vue'
import Place from './components/Place.vue'
import Hotel from './components/Hotel.vue'
import About from './components/About.vue'
import Subcribe from './components/Subcribe.vue'
import Sponsor from './components/Sponsor.vue'
import Footer from './components/Footer.vue'
import Scroll from './components/Scroll.vue'


export default {
  name: 'App',
  data: () => ({
    //
  }),
  components: {
    Barnav,
    Home,
    About,
    Experience,
    Video,
    Place,
    Hotel,
    Subcribe,
    Sponsor,
    Footer,
    Scroll
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
}
</style>
