<template>
  <div class="home">
    <Nav />
    <Welcome/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import Nav from "@/components/Nav.vue";
import Welcome from "@/components/Welcome.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Nav,
    Footer,
    Welcome
  }
};
</script>
