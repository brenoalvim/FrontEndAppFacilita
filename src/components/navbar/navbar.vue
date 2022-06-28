<template>
  <div class="navbar">
    <nav>
      <div class="logo">
        <img src="../../assets/img/facilitalogo.png" alt="" />
      </div>
      <div class="list">
        <ol>
          <li class="active">
            <div class="icon">
              <img src="../../assets/img/dashboard.png" alt="" />
            </div>
            <div class="span">
              <span>
                Dashboard
              </span>
            </div>
          </li>
          <li>
            <div class="icon">
              <img src="../../assets/img/tarefas.png" alt="" />
            </div>

            <div class="span">
              <span>
                Tarefas
              </span>
            </div>
          </li>
          <li>
            <div class="icon">
              <img src="../../assets/img/config.png" alt="" />
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
