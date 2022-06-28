<template>
  <div class="login">
    <div class="info">
      <div class="logo">
        <img src="../assets/img/facilitalogo.png" alt="" />
      </div>
      <div class="br"></div>
      <span class="title">
        <strong>FACILITA</strong>
        TASKS
      </span>
      <div class="br"></div>
      <span class="subtitle">Gestão de tarefas pessoais</span>
    </div>
    <div class="form" id="form">
      <div>
        <span class="bold">
          Entre com seus dados de acesso.
        </span>
        <div class="br"></div>
        <div class="input">
          <label for="">Nome de usuário ou e-mail:</label>
          <div class="br"></div>
          <input type="text" class="username" name="" />
          <div class="br"></div>
          <label for="">Senha:</label>
          <div class="br"></div>
          <input type="password" class="password" name="" />
          <div class="br"></div>
          <button class="buttonLogin" v-on:click="getValues()">
            Entrar
          </button>
          <div class="br"></div>
          <a href="#">
            Esqueci minha senha
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
  methods: {
    getValues() {
      const username = document.querySelector(".username");
      const password = document.querySelector(".password");
      this.sendValues(username.value, password.value);
    },

    sendValues(username, password) {
      if (username == "root" && password == "root") {
        this.$router.push("/dashboard");
      } else {
        alert(
          "Usuário ou Senha incorretos. Tente username: root password: root"
        );
      }
    }
  }
};
</script>

<style scoped>
@import "../assets/style/login.styl";
</style>
