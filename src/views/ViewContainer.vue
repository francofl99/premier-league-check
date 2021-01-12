<template>
  <div class=" w-screen h-screen bg-gray-200 ">
    <NavBar />
    <slot />
  </div>
</template>

<script>
import NavBar from "../components/NavBar";
export default {
  name: "ViewContainer",

  components: {
    NavBar,
  },
};
</script>

<style></style>
