<template>
  <div >
    <div class="h-100">
      <main class="container d-flex flex-column">
        <div align="center"><button class="btn  btn-primary w-50" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasTop" aria-controls="offcanvasTop" >Menu</button></div>
        <div class="offcanvas offcanvas-top h-25" tabindex="-1" id="offcanvasTop" aria-labelledby="offcanvasTopLabel">
            <div class="offcanvas-header border border-end-0">
              <h5 class="offcanvas-title " id="offcanvasTopLabel">Olá "Name do User"</h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body pt-1">
                <div align="center">
                  <h3 class="border border-end">Meu Perfil</h3>
                  <h3 class="border border-end">Meus Documentos</h3>
                  <h3 class="border border-end">Ajuda</h3>
                  <h3 class="border border-end">Sair</h3>
                </div>
            </div>
        </div>


        <Nuxt/>

        <footer class="w-100 bg-light border-top d-flex align-items-center justify-content-center">
          <div class="text-center fs-6 text-muted">
            Copyright © 2022 <a href="https://www.beepp.com.br" class="fw-bold text-primary text-warning">BeeApp</a>.
          </div>
        </footer>

      </main>

    </div>

  </div>
</template>

<script>
export default {
  name: "testeMain"
}
</script>

<style scoped>

</style>
