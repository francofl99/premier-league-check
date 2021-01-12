<template>
  <div class="image bg-cover w-screen h-screen ">
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

<style>
.image {
  background-image: url("../assets/PREMIER.jpeg");
}
</style>
