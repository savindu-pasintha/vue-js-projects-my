<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Navbar/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Navbar from "@/components/Navebar.vue";

export default {
  /*
  name: "Home",
  components: {
    HelloWorld
  }
},
export default {
  name: "Home",
  components: {
    HelloWorld
  },

  */

  name: "Navbar",
  components:{
    Navbar
  }
};
</script>
