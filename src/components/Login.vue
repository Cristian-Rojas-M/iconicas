<template>
  <div class="container-fluid">
    <div class="row h-100">
      <div class="col container-logo d-none d-lg-block">
        <div class="h-100 d-flex align-items-center">
          <img
            class="img-fluid"
            alt="logo iconas de la moda"
            src="@/assets/logo_iconicas.svg"
          />
        </div>
      </div>
      <div class="col">
        <div class="row d-flex justify-content-center">
          <h2 class="fw-bold text-center my-5">Bienvenido</h2>
          <div class="col-8">
            <div class="form-floating my-3">
              <input
                type="email"
                class="form-control"
                id="floatingInput"
                placeholder="name@example.com"
              />
              <label for="floatingInput">Email</label>
            </div>
            <div class="form-floating">
              <input
                type="password"
                class="form-control"
                id="floatingPassword"
                placeholder="Password"
              />
              <label for="floatingPassword">Password</label>
            </div>
            <div class="d-grid mt-4">
              <button class="btn btn-primary" type="submit">
                Inicias sesion
              </button>
            </div>
            <div class="my-3">
              <span>No tenes cuenta ?</span>
              <br />
              <span>Recuperar password</span>
            </div>
          </div>
          <div class="row text-center mt-3">
            <span>Iniciar secion</span>
            <div class="col d-flex justify-content-center mt-3">
              <button class="btn btn-outline-primary m-2 button">
                <i class="bi bi-facebook fs-4"></i>
                Facebook
              </button>
              <button class="btn btn-outline-danger m-2 button">
                <i class="bi bi-instagram fs-4"></i>
                Gmail
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.container-fluid {
  height: 100vh;
}
.container-logo {
  background-color: #f9cdff;
}
.button{
  height: 2.5rem;
  width: 8rem;
}
</style>
