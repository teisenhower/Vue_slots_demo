<template>
  <div id="app">
    <Card> </Card>
  </div>
</template>

<script>
import Card from "@/components/Card";

export default {
  name: "App",
  components: {
    Card,
  },
};
</script>

<style>
body {
  background: rgb(230, 230, 230);
}
#app {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
