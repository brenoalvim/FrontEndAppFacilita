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
  --active-color: #1182f2;
  --aside-color: #f4fbff;
  --main-color: #e9f4fb;
  --font-family: "gilroy", arial;
}
</style>
