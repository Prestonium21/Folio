<template>
  <div class="home">
    <img alt="Professional Photo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to My Portfolio" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
<style scoped>
.home {
	background-color: #234;
	min-height: 100vh;
}
</style>
