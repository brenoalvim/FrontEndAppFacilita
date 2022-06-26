<template>
  <div class="main">
    <div>
      <div class="aside">
        <div class="list">
          <ol>
            <li class="title">
              Categorias
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
      <div class="container-main">
        <div class="tasks">
          <div class="title">
            <span>Minhas Tarefas</span>
          </div>
          <div class="description">
            <span>
              Olá <span class="name">Breno Alvim</span>, você tem
              <span class="theAmout">4 tarefas</span>
            </span>
          </div>
          <div class="search"></div>
          <div class="task"></div>
        </div>
      </div>
    </div>
    <button class="addTasks" v-on:click="openModal()">
      <img src="../../assets/plus.png" alt="" />
    </button>
    <div class="modal"></div>
  </div>
</template>

<script>
export default {
  name: "MainDashboard",
  methods: {
    openModal() {
      alert("Hello");
    }
  }
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
  padding-bottom: 55px;
  font-weight: bold;
  font-size: 17px;
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
  gap: 15px;
}

.container-main {
  display: flex;
  justify-content: center;
  align-items: center;
  min-width: 85vw;
}

.container-main .tasks {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  width: 50%;
  height: 70%;
  border: 1px solid red;
}

.addTasks {
  position: fixed;
  width: 75px;
  height: 75px;
  bottom: 25px;
  right: 25px;
  background: var(--green-color);
  border-radius: 50%;
  border: none;
}

</style>
