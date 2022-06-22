<template>
  <div class="login">
    <div class="info">
      <!-- <div class="image"> -->
        <!-- <img src="../assets/facilita.png" alt="" /> -->
      <!-- </div> -->
      <span class="title"> <strong>FACILITA</strong>TASK </span>
      <span class="subtitle">
        Gestão de tarefas pessoais
      </span>
    </div>
    <div class="form"></div>
  </div>
</template>

<script>
export default {
  name: "Login"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.login {
  width: 100vw;
  height: 100vh;
  background: var(--light-color);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.form,
.info {
  display: flex;
  justify-content: center;
  align-content: center;
  height: 100vh;
}

.info {
  width: 40%;
  background: var(--brand-color);
}

.form {
  width: 59.89%;
}

.info .image {
  display: flex;
  justify-content: center;
  align-content: center;
  width: 100%;
  height: 100%;
}

.info img {
  width: 100px;
  height: 100px;
  border-radius: 8px;
}

.info span {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
</style>
