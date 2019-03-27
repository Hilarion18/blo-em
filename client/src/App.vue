<template>
  <div id="app">
    <div id="nav">
      <navbar></navbar>
    </div>
    <router-view/>
    <footer style="background-color: rgb(245, 86, 7);margin-top: 100px">
      <footer-bot></footer-bot>
    </footer>
  </div>
</template>

<script>
import Navbar from '@/components/navbar/Navbar.vue'
import FooterBot from '@/components/footer/Footer.vue'

export default {
  components: {
    Navbar,
    FooterBot
  }
}
</script>

<style>

#app {
  background-image: url("../src/assets/img/DSC07272.png");
  /* background-color: rgb(245, 86, 7); */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

</style>
