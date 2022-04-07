<template>
  <div>
    <script
      src="https://kit.fontawesome.com/0ab2bcde1c.js"
      crossorigin="anonymous"
    ></script>
    <Header />
    <div class="search">
      <div>
        <div>
          <b-form-input placeholder="Buscar Veículo..."></b-form-input>
        </div>
      </div>
    </div>
    <Nuxt />
    <div class="footer">
      <div class="footer-logo">
        <a href="/"> <b-img src="~/assets/img/logo.png" alt=""></b-img></a>
      </div>
      <div class="container">
        <div class="footer-grid">
          <div class="text-footer">
            <h5>
              HORÁRIO DE ATENDIMENTO<br />
              DE SEGUNDA A SEXTA, DAS 08:00 ÀS 18:30<br />
              SÁBADO DAS 08:00 ÀS 17:30
            </h5>
          </div>
          <div class="center">
            <h5>
              CONSIGNAÇÃO E COMPRA<br />
              41 3311-1858 41<br />
              99753-2000
            </h5>
          </div>
          <div>
            <h5>
              ENDEREÇO<br />
              Rua Marechal Floriano Peixoto, 6825 - Boqueirão - Curitiba
            </h5>
          </div>
        </div>
        <div class="footer-icons">
          <div class="d-flex justify-content-center">
            <div class="mx-2" @click="whatsappUrl">
              <img src="~/assets/img/whatsapp2.svg" alt="" />
            </div>
            <div class="mx-2" @click="instagramUrl">
              <img src="~/assets/img/instagram2.svg" alt="" />
            </div>
            <div class="mx-2">
              <img src="~/assets/img/youtube2.svg" alt="" />
            </div>
            <div class="mx-2">
              <img src="~/assets/img/facebook2.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "",

  data() {
    return {};
  },

  methods: {
    whatsappUrl() {
      window.open(
        "https://api.whatsapp.com/send?phone=5541997532000&text=Vim%20pelo%20site",
        "_blank"
      );
    },
    instagramUrl() {
        window.open(
        "https://www.instagram.com/zero41motors_curitiba/",
        "_blank"
      );
    },
  },
};
</script>
<style>
</style>
