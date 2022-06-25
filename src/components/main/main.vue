<template>
  <div class="main">
    <div>
      <div class="aside">
        <div class="list">
          <ol>
            <li class="title">
              Categoria
            </li>
            <a href="#">
              <li class="active">
                <img src="../../assets/arrowblue.png" alt="" />
                Todas
              </li>
            </a>
            <a href="#">
              <li>
                <img src="../../assets/arrow.png" alt="" />
                Urgentes
              </li>
            </a>
            <a href="#">
              <li>
                <img src="../../assets/arrow.png" alt="" />
                Importantes
              </li>
            </a>
            <a href="#">
              <li>
                <img src="../../assets/arrow.png" alt="" />
                Outras
              </li>
            </a>
            <a href="#">
              <li>
                <img src="../../assets/arrow.png" alt="" />
                Finalizadas
              </li>
            </a>
          </ol>
        </div>
      </div>
      <div class="container-main"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainDashboard"
};
</script>

<style scoped>
.main {
  position: fixed;
  height: 85vh;
  width: 95vw;
  top: 10vh;
  left: 5vw;
  height: 90vh;
  z-index: -1;
  background: var(--main-color);
}
.main div {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
}

.aside {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  width: 10vw;
  min-width: 220px;
  /* padding-left: 15vw; */
  background: var(--aside-color);
  -webkit-box-shadow: -5px 11px 15px 5px rgba(0, 0, 0, 0.35);
  box-shadow: -5px 11px 15px 5px rgba(0, 0, 0, 0.35);
}

.aside .list {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 15px;
  margin-top: -110px;
}

.aside .list ol .title {
  padding-bottom: 25px;
  font-weight: bold;
}

.aside .list ol .active {
  color: var(--brand-color);
}

.aside .list ol a {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  list-style: none;
  text-decoration: none;
  padding-bottom: 25px;
  font-weight: bold;
  color: #000;
}

.aside .list ol li {
  display: flex;
  justify-content: start;
  align-items: center;
  padding-left: 25px;
  width: 100%;
  gap: 5px;
}

.container-main {
  display: flex;
  justify-content: center;
  align-items: center;
  min-width: 85vw;
  border: 1px solid red;
}
</style>
