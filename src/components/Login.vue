<template>
  <div class="col-4 border rounded">
    <form>
      <!--  -->
      <h1 class="h3 mb-3 fw-normal text-center">Ingreso Clientes</h1>

      <!-- Input Rut -->
      <div class="form-floating mb-3">
        <label class="text-muted" for="floatingInput">Rut</label>
        <input
          type="rut"
          class="form-control"
          id="floatingInput"
          placeholder="name@example.com"
        />
      </div>

      <!-- Input Password -->
      <div class="form-floating mb-3">
        <label class="text-muted" for="floatingPassword">Contraseña</label>
        <input
          type="password"
          class="form-control"
          id="floatingPassword"
          placeholder="Password"
        />
      </div>

      <!--  -->
      <button class="w-100 btn btn-lg btn-primary" type="submit">
        Ingresar
      </button>
      <p class="mt-5 mb-3 text-muted"></p>
    </form>
  </div>
</template>

<script>
export default {
  name: "Login",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
