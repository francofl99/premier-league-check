<template>
  <ViewContainer>
    <div class=" grid grid-cols-5 gap-4 w-full h-9/10 p-4">
      <Container class=" w-full h-full" />
      <Container class=" w-full h-1/2 self-center col-span-3" />
      <Container class=" w-full h-full" />
    </div>
  </ViewContainer>
</template>

<script>
import ViewContainer from "./ViewContainer";
import Container from "../components/Container";
export default {
  name: "MainView",

  components: {
    ViewContainer,
    Container,
  },
};
</script>

<style></style>
