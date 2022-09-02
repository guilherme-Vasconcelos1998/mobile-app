<template>

  <div id="beeapp">
    <div v-if="userType === 'admin'" class="w-100 bg-warning border-bottom border-2 border-dark py-2 px-4">
      Você esta gerenciando a empresa: <b>{{ $auth.user.dados_conta.pessoa.nome_fantasia }}</b>
    </div>
    <div id="app-pages">
      <div class="d-flex h-100">
        <aside class="bg-secondary">
          <div class="side-bar">
            <SideBar></SideBar>
          </div>
        </aside>
        <main class="flex-fill d-flex flex-column">
          <header class="bg-secondary-gradient-dark-horizontal shadow d-flex align-items-center">

            <NuxtLink to="/help/form" class="ms-4 text-white fs-6">

              <i class="fal fa-user-headset"></i> Abrir Chamado

            </NuxtLink>

            <div class="dropdown">
              <a class="ms-4 dropdown-toggle text-white fs-6" href="#" data-bs-toggle="dropdown">
                <i class="fal fa-star me-2"></i> Favoritos
              </a>

              <ul class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                <li><a class="dropdown-item" href="#">Nenhum favorito adicionado</a></li>
              </ul>
            </div>

            <div class="mx-4 barra-busca">
              <div class="input-group">
                <input type="text" class="form-control" placeholder="O que você esta procurando?">
                <div class="bg-primary rounded-end px-3 text-white fs-4 d-flex align-items-center">
                  <i class="fab fa-searchengin"></i>
                </div>
              </div>
            </div>

            <div class="ms-auto pe-4 d-flex align-items-center">


              <a class="text-white fs-5 me-4" href="#" data-bs-toggle="offcanvas"
                 data-bs-target="#offcanvasAjuda">
                <i class="fal fa-life-ring"></i>
              </a>


              <div class="dropdown">
                <a class="ms-4 dropdown-toggle text-white fs-6" href="#" data-bs-toggle="dropdown">
                  <i class="fal fa-bell me-2"></i> Notificações
                </a>

                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Nenhuma notificação</a></li>
                </ul>
              </div>


              <div class="dropdown">
                <a class="ms-4 dropdown-toggle text-white" href="#" data-bs-toggle="dropdown">
                  <img src="https://via.placeholder.com/100x100"
                       class="avatar-50 rounded-circle border-white border-2"/>
                </a>

                <ul class="dropdown-menu">
                  <li>
                    <a class="dropdown-item" href="#">
                      <i class="fal fa-user me-2"></i> Meu Perfil
                    </a>
                  </li>
                  <li><hr class="dropdown-divider"></li>
                  <li>
                    <a class="dropdown-item" href="#" @click.prevent="logout">
                      <i class="far fa-sign-out me-2"></i> Sair
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </header>

          <Nuxt/>

          <footer class="w-100 bg-light border-top d-flex align-items-center justify-content-center">
            <div class="text-center fs-6 text-muted">
              Copyright © 2022 <a href="https://www.beepp.com.br" class="fw-bold text-primary">BeeApp</a>.
            </div>
          </footer>
        </main>
      </div>


      <div id="offcanvasAjuda" class="offcanvas offcanvas-end" tabindex="-1">
        <div class="offcanvas-header">
          <h5 class="offcanvas-title">
            <i class="fal fa-life-ring me-2"></i>
            Tópicos de Ajuda
          </h5>
          <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas"
                  aria-label="Close"></button>
        </div>
        <div class="offcanvas-body border-top">
          <div class="text-muted">
            Temos alguns materiais que podem auxiliar no uso da plataforma.
          </div>
          <div class="list-group mt-3">

            <a href="#" class="list-group-item list-group-item-action d-flex">
              <div class="me-3">
                <i class="fal fa-books text-secondary"></i>
              </div>
              <div class="text-primary">
                Um tópico de ajuda.
              </div>
            </a>

            <a href="#" class="list-group-item list-group-item-action d-flex">
              <div class="me-3">
                <i class="fal fa-books text-secondary"></i>
              </div>
              <div class="text-primary">
                Um tópico de ajuda.
              </div>
            </a>

            <a href="#" class="list-group-item list-group-item-action d-flex">
              <div class="me-3">
                <i class="fal fa-books text-secondary"></i>
              </div>
              <div class="text-primary">
                Um tópico de ajuda.
              </div>
            </a>


          </div>
        </div>
      </div>

    </div>

  </div>


</template>

<script>
export default {
  name: "teste"
}
</script>

<style scoped>

</style>
