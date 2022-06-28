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
              <span class="quantity">4 tarefas</span>
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
@import '../../assets/style/main.styl';
</style>
