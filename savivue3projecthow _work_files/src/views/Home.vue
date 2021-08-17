<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
     <h1>Vue ss js</h1>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/views/newvue.vue";

//import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>

<style>
.home{
  border:2px solid yellow;
}
</style>
