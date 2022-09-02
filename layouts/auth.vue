<template>
  <div id="auth_page" class="p-3 mb-2 bg-dark text-white">
    <div class="top h-100 ">
      <div class="container h-100 d-flex flex-column">
        <div class="d-flex justify-content-center">
          <a href="#">
            <img class="logo d-block d-md-none mt-5 " src="~assets/media/images/logos/logo-v2.png" />
            <img class="logo d-none d-md-block mt-5 " src="~assets/media/images/logos/logo-v1.png" />
          </a>
        </div>
        <div class="flex-fill d-flex align-items-center">
          <Nuxt/>
        </div>
        <div class="footer">
          <div class="text-end pb-2 d-none d-lg-block">
            Beeapp Gestão Corporativa LTDA © - CNPJ: 44.999.343/0001-87
            <a class="ms-4 text-primary" href="#">Política de Privacidade</a>
            <a class="ms-2 text-primary" href="#">Ajuda</a>
          </div>
          <div class="text-center pb-2 d-block d-lg-none">
            Beeapp Gestão Corporativa LTDA ©<br/>
            <b>CNPJ:</b> 44.999.343/0001-87 <br/>
            <a class="text-warning" href="#">Política de Privacidade</a>
            <a class="ajuste text-warning ms-4" href="#">Ajuda</a>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "auth"
}
</script>

<style >

</style>
