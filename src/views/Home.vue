<template>
  <div class="home">
    <img alt="VVS logo" src="../assets/logo.png" style="width: 45vw" />
    <HelloWorld msg="VVS Rocks" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
