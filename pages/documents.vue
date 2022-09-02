<template>
  <div class="documentsPage ">
    <div class="h-100">
      <div class="container h-100 d-flex flex-column">
        <div class="justify-content-center"><h2>Documentação</h2></div>
        <div class="accordion  accordion-flush" id="accordionFlushExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingOne">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                Minhas Atribuições
              </button>
            </h2>
            <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body p-2">
                <div class="searchCampoMa mb-2">
                  <div class="input-group">
                    <input type="text" class="form-control" placeholder="Pesquisar" aria-label="Recipient's username" aria-describedby="button-addon2">
                    <button class="btn btn-outline-secondary" type="button" id="button-addon2"><i class="fab fa-searchengin"></i></button>
                  </div>
                </div>
                <div>
                  <!-- Button trigger modal -->
                  <button type="button" class="list-group-item list-group-item-action mb-2" aria-current="true" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <i class="fal fa-tasks me-2"></i>Atribuições Pessoais
                  </button>
                  <button type="button" class="list-group-item list-group-item-action mb-2" aria-current="true" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <i class="fal fa-tasks me-2"></i>Atribuições Pessoais e do Setor
                  </button></button>
                  <button type="button" class="list-group-item list-group-item-action mb-2" aria-current="true" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <i class="fal fa-tasks me-2"></i>Atribuições Pessoais e do Setor Financeiro
                  </button></button>
                  <button type="button" class="list-group-item list-group-item-action mb-2" aria-current="true" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <i class="fal fa-tasks me-2"></i>Atribuições Pessoais e do Setor A and B and C and F and H
                  </button></button>
                  <button type="button" class="list-group-item list-group-item-action" aria-current="true" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <i class="fal fa-tasks me-2"></i>Atribuições Pessoais e do Setor C and Y
                  </button>
                </div>
                <!-- Modal -->
                <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                  <div class="modal-dialog modal-fullscreen modal-dialog-scrollable">
                    <div class="modal-content">
                      <div class="modal-header justify-content-center">
                        <h5 class="modal-title" id="exampleModalLabel">General information</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <div class="container-fluid justify-content-center">
                          <h1>Contend</h1>
                        </div>
                      </div>
                      <div class="modal-footer justify-content-center" style="background:#888888">
                        <h1>Footer</h1>
                      </div>
                    </div>
                  </div>
                </div>
                <!--
                <div class=" modal-dialog">
                  <div class="modal-body">
                    <div class="list-group">

                       <a href="/pages/login" aria-current="true" class="list-group-item list-group-item-action"><i class="fal fa-tasks me-2"></i> Default</a>
                    </div>
                  </div>
                </div>
                -->
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingTwo">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                Normativas
              </button>
            </h2>
            <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingThree">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                Procedimentos Operacionais
              </button>
            </h2>
            <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingFour">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseFour" aria-expanded="false" aria-controls="flush-collapseFour">
                Diagramas
              </button>
            </h2>
            <div id="flush-collapseFour" class="accordion-collapse collapse" aria-labelledby="flush-headingFour" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  layout: 'main',
  name: "documents",

}
</script>

<style scoped>

</style>
