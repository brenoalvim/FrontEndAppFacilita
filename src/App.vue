<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
* {
  padding: 0px;
  margin: 0px;
  font-family: "gilroy", arial;
}

:root {
  --brand-color: #2693ff;
  --light-color: #ffffff;
  --active-color: #1182F2;
  --font-family: "gilroy", arial;
}
</style>
