<template>
  <div class="dashboard">
    <Navbar />
    <HeaderDashboard />
  </div>
</template>

<script>
import Navbar from "../components/navbar/navbar.vue";
import HeaderDashboard from "../components/header/header.vue";
export default {
  name: "Dashboard",
  components: { Navbar, HeaderDashboard }
};
</script>

<style scoped></style>
