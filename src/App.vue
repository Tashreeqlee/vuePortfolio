<template>
  <Navbar/>
  <main class="container-fluid">
  <router-view/>
  </main>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';



export default {
  components:{
    Navbar,
    Footer
  }

}
</script>

<style src="@/assets/css/style.css"></style>
