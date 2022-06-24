<template>
  <div id="app">
    <link
      rel="shortcut icon"
      href="../src/assets/facilita.png"
      type="image/x-icon"
    />
    <Login v-if="login == true" />
    <Dashboard />
  </div>
</template>

<script>
import Login from "./components/Login";
import Dashboard from "./components/Dashboard";

export default {
  name: "App",
  components: {
    Login,
    Dashboard
  },

  data() {
    return {
      login: true,
      dashboard: false
    };
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
