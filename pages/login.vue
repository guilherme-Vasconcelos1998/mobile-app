<template>
  <div class="login w-100 mb-5 pb-5">
    <div class="row align">
      <div class="col-lg-4 offset-lg-4 ">
        <div class="d-flex flex-column ps-5 pe-5">
          <h1 class="fw-light text-center">Login</h1>
          <div class="detalheTitulo"></div> <!-- Uma possível interação no 'hq1' Login -->
        </div>
        <div>
          <div class="form-floating mb-3">
            <input type="email" class="form-control text-black rounded-5" id="floatingInput" placeholder="usuario@email.com ou 000.000.000-00">
            <label class="fw-normal text-black" for="floatingInput">Usuário, e-mail ou CPF:</label>
          </div>
          <div class="form-floating">
            <input type="password" class="form-control fw-normal text-black rounded-5" id="floatingPassword" placeholder="Password">
            <label class="fw-normal text-black" for="floatingPassword">Password:</label>
          </div>
        </div>
        <div>
          <div class="position-relative mb-2">
            <div class="position-absolute top-0 start-0"><input type="checkbox" class="form-check-input">
              <label class="form-check-label text-primary">Salvar Senha</label>
            </div>
            <div class="position-absolute top-0 end-0">
              <a class="" href="#">Esqueci a Senha</a>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-center align-items-center my-5">
          <NuxtLink to="/documents"><button type="submit" class="btn btn-primary px-3">Submit</button></NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'auth'
}
</script>

<style scoped>

</style>
