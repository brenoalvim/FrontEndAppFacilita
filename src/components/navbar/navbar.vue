<template>
  <div class="navbar">
    <nav>
      <div class="logo">
        <img src="../../assets/facilitalogo.png" alt="" />
      </div>
      <div class="list">
        <ol>
          <li class="active">
            <div class="icon">
              <img src="../../assets/dashboard.png" alt="" />
            </div>
            <div class="span">
              <span>
                Dashboard
              </span>
            </div>
          </li>
          <li>
            <div class="icon">
              <img src="../../assets/tarefas.png" alt="" />
            </div>

            <div class="span">
              <span>
                Tarefas
              </span>
            </div>
          </li>
          <li>
            <div class="icon">
              <img src="../../assets/config.png" alt="" />
            </div>
            <div class="span">
              <span>
                Dashboard
              </span>
            </div>
          </li>
        </ol>
      </div>
      <div class="white-space"></div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
@import "../../assets/style/navbar.styl";
</style>
