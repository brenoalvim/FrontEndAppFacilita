<template>
  <div class="header">
    <header>
      <div class="info">
        <div>
          <div class="avatar">
            <img
              src="https://avatars.githubusercontent.com/u/39434668?v=4"
              alt=""
            />
          </div>
          <div class="span">
            <div class="name">
              <span>
                Breno Alvim
              </span>
            </div>
            <div class="title">
              <span>
                Front-end Developer
              </span>
            </div>
          </div>
        </div>
      </div>
    </header>
    <MainDashboard />
  </div>
</template>

<script>
import MainDashboard from "../main/main.vue";
export default {
  name: "HeaderDashboard",
  components: { MainDashboard }
};
</script>

<style scoped>
@import "../../assets/style/header.styl";
</style>
