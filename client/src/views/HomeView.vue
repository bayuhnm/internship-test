<template>
  <div class="home">
    <TheNavbar />
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import TheNavbar from "@/components/TheNavbar.vue";
import HelloWorld from "../components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    TheNavbar,
    HelloWorld,
  },
};
</script>


