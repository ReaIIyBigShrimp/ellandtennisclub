<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Nav />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import Nav from "@/components/Nav.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Nav,
    Footer
  }
};
</script>
