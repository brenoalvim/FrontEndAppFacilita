<template>
  <div class="login">
    <div class="info">
      <div class="logo">
        <img src="../assets/facilitalogo.png" alt="" />
      </div>
      <div class="br"></div>
      <span class="title">
        <strong>FACILITA</strong>
        TASKS
      </span>
      <div class="br"></div>
      <span class="subtitle">Gestão de tarefas pessoais</span>
    </div>
    <div class="form">
      <div>
        <span class="bold">
          Entre com seus dados de acesso.
        </span>
        <div class="br"></div>
        <div class="input">
          <label for="">Nome de usuário ou e-mail:</label>
          <div class="br"></div>
          <input type="text" name="" id="" />
          <div class="br"></div>
          <label for="">Senha:</label>
          <div class="br"></div>
          <input type="text" name="" id="" />
          <div class="br"></div>
          <button>
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
  flex-wrap: wrap;
  height: 100vh;
}

.info {
  width: 40%;
  min-width: 375px;
  background: var(--brand-color);
}

.form {
  width: 59.89%;
}

.info .logo {
  display: flex;
  justify-content: start;
  align-content: center;
  min-width: 375px;
  width: 50%;
}

.info .title,
.info .subtitle {
  display: flex;
  justify-content: start;
  align-content: center;
  min-width: 375px;
  width: 50%;
  color: var(--light-color);
}

.info .title {
  font-size: 45px;
}

.info .subtitle {
  font-size: 17px;
}

.br {
  width: 100%;
  height: 1px;
}

.form div {
  display: flex;
  justify-content: start;
  align-items: center;
  flex-wrap: wrap;
  width: 30%;
  min-width: 370px;
}

.form div .bold {
  font-weight: bold;
  margin-bottom: 20px;
}

.form div .input label {
  font-size: 13px;
  font-weight: bold;
  margin-top: 15px;
  color: #6b7e90;
}

.form div .input input {
  width: 300px;
  height: 45px;
  border: 2px solid #c3dcec;
  font-size: 16px;
  padding-left: 5px;
  border-radius: 5px;
  outline: none;
}

.form div .input input:focus {
  border: 2px solid var(--brand-color);
}

.form div .input button {
  width: 310px;
  margin-top: 15px;
  background: #1ad18f;
  border: none;
  height: 45px;
  border-radius: 5px;
  color: var(--light-color);
  font-weight: bold;
}

.form div .input a {
  text-decoration: underline;
  font-size: 12px;
  font-weight: bold;
  margin-top: 35px;
  color: var(--brand-color);
}

@media (max-width: 934px) {
  .info {
    width: 100%;
    min-width: 375px;
    height: 25vh;
  }

  .form {
    width: 100%;
    min-width: 375px;
    height: 90vh;
    margin-top: -15vh;
  }
}
</style>
