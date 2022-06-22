<template>
  <div id="app">
    <link
      rel="shortcut icon"
      href="../src/assets/facilita.png"
      type="image/x-icon"
    />
    <Login />
  </div>
</template>

<script>
import Login from "./components/Login";

export default {
  name: "App",
  components: {
    Login
  }
};
</script>

<style>
:root {
  --brand-color: #2693ff;
  --light-color: #ffffff;
  --font-family: "gilroy", arial;
}
* {
  font-family: "gilroy", arial;
  margin: 0;
  padding: 0;
}
html {
  display: flex;
  justify-content: center;
  align-content: center;
}
</style>
