<template >
  <div>
    <div class="header">
      <div class="container">
        <div class="row align-items-center">
          <div class="logo">
            <a href="/"> <b-img src="~/assets/img/logo.png" alt=""></b-img></a>
          </div>
          <div class="mx-auto">
            <div class="mx-auto">
              <b-navbar toggleable="lg" type="dark" variant="">
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

                <b-collapse id="nav-collapse" is-nav>
                  <b-navbar-nav>
                    <b-nav-item href="#">ESTOQUE</b-nav-item>
                    <b-nav-item href="#">VENDA SEU CARRO</b-nav-item>
                    <b-nav-item href="#">FINANCIE</b-nav-item>
                    <b-nav-item href="#">SOBRE</b-nav-item>
                    <b-nav-item href="#">CONTATO</b-nav-item>
                  </b-navbar-nav>

                  <!-- Right aligned nav items -->
                  <b-navbar-nav class="ml-auto"> </b-navbar-nav>
                </b-collapse>
              </b-navbar>
            </div>
          </div>
          <div class="d-flex mx-auto align-items-center">
            <div class="phone-top">
              <h4>41 99999-9999</h4>
            </div>
            <div class="whatsapp-top">
              <b-img
                src="~/assets/img/whatsapp.svg"
                alt=""
                class="img-fluid"
              ></b-img>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="header-mobile">
      <div class="header-grid-m">
        <div>
          <div class="logo">
            <a href="/"> <b-img src="~/assets/img/logo.png" alt=""></b-img></a>
          </div>
        </div>
        <div class="btn-menu">
          <button><i class="fas fa-bars"></i></button>
        </div>
      </div>
      <div>
        <div class="d-flex mx-auto align-items-center justify-content-center pb-3">
          <div class="phone-top">
            <h4>41 99999-9999</h4>
          </div>
          <div class="whatsapp-top">
            <b-img
              src="~/assets/img/whatsapp.svg"
              alt=""
              class="img-fluid"
            ></b-img>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="">
</style>
