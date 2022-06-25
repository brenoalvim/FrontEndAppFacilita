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
nav {
  position: fixed;
  z-index: 10;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  height: 100vh;
  width: 5vw;
  min-width: 80px;
  background: var(--brand-color);
}

nav .logo {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 10vh;
  margin-top: -145px;
}

nav .logo img {
  width: 75px;
  height: 75px;
}

nav .list {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin-top: -15px;
}

nav .list ol {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin: 0 auto;
}

nav .list ol li {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin: 0 auto;
  color: var(--light-color);
  font-weight: bold;
  font-size: 12px;
  height: 75px;
  width: 100%;
  border-top: 1px solid #7eb9f5;
  border-bottom: 1px solid #7eb9f5;
  cursor: pointer;
}

nav .list ol li:hover {
  background: var(--active-color);
}

nav .list ol li .icon {
  width: 100%;
  text-align: center;
}

nav .list ol li .icon img {
  width: 40px;
}

.active {
  background: var(--active-color);
}

nav .white-space {
  display: flex;
  justify-content: center;
  align-items: center;
  /* width: 100%; */
}
</style>
