<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="https://dicas.olx.com.br/wp-content/uploads/2021/04/tipos-de-carros-capa.png"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide
        img-src="https://dicas.olx.com.br/wp-content/uploads/2021/01/carros-mais-vendidos-2021.png"
      >
      </b-carousel-slide>
    </b-carousel>
    <div class="text-center my-4 text-main">
      <h4>FILTRE NOSSOS VEÍCULOS POR <span>MARCA</span></h4>
    </div>
    <div class="container">
      <div class="marcas">
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/bmw.svg" alt=""></b-img>
            </div>
            <div>
              <p>BMW</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/jeep.svg" alt=""></b-img>
            </div>
            <div>
              <p>JEEP</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/hyundai.svg" alt=""></b-img>
            </div>
            <div>
              <p>HYUNDAI</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/toyota.svg" alt=""></b-img>
            </div>
            <div>
              <p>TOYOTA</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/ford.svg" alt=""></b-img>
            </div>
            <div>
              <p>FORD</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/honda.svg" alt=""></b-img>
            </div>
            <div>
              <p>HONDA</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/fiat.svg" alt=""></b-img>
            </div>
            <div>
              <p>FIAT</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/mercedez.svg" alt=""></b-img>
            </div>
            <div>
              <p>MERCEDES-BENZ</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/renault.svg" alt=""></b-img>
            </div>
            <div>
              <p>RENAULT</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/volkswagen.svg" alt=""></b-img>
            </div>
            <div>
              <p>VOLKSWAGEN</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/chevrolet.svg" alt=""></b-img>
            </div>
            <div>
              <p>CHEVROLET</p>
            </div>
          </div>
        </div>
        <div class="marca1">
          <div class="d-flex flex-column align-items-center p-3 itens">
            <div>
              <b-img src="~/assets/img/mitsubish.svg" alt=""></b-img>
            </div>
            <div>
              <p>MITSUBISHI</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center my-4 text-main">
      <h4>VEÍCULOS EM <span>DESTAQUE</span></h4>
    </div>
    <div class="container">
      <div class="product-grid">
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://i0.statig.com.br/bancodeimagens/cx/ao/52/cxao52zsjbdga37o117pghrdp.jpg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://i0.statig.com.br/bancodeimagens/cx/ao/52/cxao52zsjbdga37o117pghrdp.jpg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://s2.glbimg.com/FQRJbVOV0NhOt1j-RhPrSecSl_M=/0x0:6000x4000/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_cf9d035bf26b4646b105bd958f32089d/internal_photos/bs/2021/V/P/1orXdhRTWkU72iEH677Q/fiatargotrekking13dianteira-1.jpeg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://s2.glbimg.com/FQRJbVOV0NhOt1j-RhPrSecSl_M=/0x0:6000x4000/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_cf9d035bf26b4646b105bd958f32089d/internal_photos/bs/2021/V/P/1orXdhRTWkU72iEH677Q/fiatargotrekking13dianteira-1.jpeg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://s2.glbimg.com/FQRJbVOV0NhOt1j-RhPrSecSl_M=/0x0:6000x4000/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_cf9d035bf26b4646b105bd958f32089d/internal_photos/bs/2021/V/P/1orXdhRTWkU72iEH677Q/fiatargotrekking13dianteira-1.jpeg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div>
          <a href="">
            <div class="product">
              <div class="product-img">
                <img
                  src="https://i0.statig.com.br/bancodeimagens/cx/ao/52/cxao52zsjbdga37o117pghrdp.jpg"
                  alt=""
                />
              </div>
              <div class="product-desc">
                <div>
                  <h4>FIAT TORO - 1.0</h4>
                  <h6>2018 - USADO - UTILITARIO</h6>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="com-grid">
        <div class="com-content">
          <div class="com-text">
            <div class="com-text-2">
              <h3>COMPRAMOS SEU VEÍCULO</h3>
              <p>
                Venda seu carro em 30 minutos com segurança e pagamento a VISTA!
              </p>
            </div>
          </div>
          <div class="com-bottom text-center">
            <button class="btn btn-danger">ENVIE SEU VEÍCULO</button>
          </div>
        </div>
        <div class="com-content">
          <div class="com-text-new">
            <div class="com-text-2">
              <h3>FINANCIE SEU SONHO</h3>
              <p>
                Trabalhamos com todas as financeiras do mercado para conseguir a
                melhor taxa para você!
              </p>
            </div>
          </div>
          <div class="com-bottom text-center">
            <button class="btn btn-danger">FAÇA UMA SIMULAÇAO</button>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center mt-5 text-main">
      <h4>SIGA-NOS NAS <span>REDES SOCIAIS</span></h4>
    </div>
    <div class="container">
      <div class="social-grid">
        <div>
          <a href="https://www.instagram.com/zero41motors_curitiba/" target="_blank">
            <div class="social-cont">
              <div class="ml-4">
                <img src="~/assets/img/instagram.svg" alt="" />
              </div>
              <div>
                <h4>@zero41motors_curitiba</h4>
              </div></div
          ></a>
        </div>
        <div>
          <a href="">
            <div class="social-cont">
              <div class="ml-4">
                <img src="~/assets/img/facebook.svg" alt="" />
              </div>
              <div>
                <h4>fb.com/zero4motors</h4>
              </div></div
          ></a>
        </div>
        <div>
          <a href="">
            <div class="social-cont">
              <div class="ml-4">
                <img src="~/assets/img/youtube.svg" alt="" />
              </div>
              <div>
                <h4>zero4motors</h4>
              </div></div
          ></a>
        </div>
      </div>
    </div>
    <div class="contact-grid">
      <div>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3601.5393430449835!2d-49.24648968479742!3d-25.487053141390803!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94dcfb29c55efc07%3A0x94d9c28d87687819!2sAv.%20Mal.%20Floriano%20Peixoto%2C%206825%20-%20Boqueir%C3%A3o%2C%20Curitiba%20-%20PR%2C%2081650-000!5e0!3m2!1spt-BR!2sbr!4v1649336411542!5m2!1spt-BR!2sbr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
      <div class="contacts">
          <h2>Zero 41 Motors</h2>
          <h5><i class="fas fa-map-marker-alt"></i> Endereço: Rua Marechal Floriano Peixoto, 6825 - Boqueirão - Curitiba</h5>
          <h5><i class="fas fa-envelope"></i> Email: zero41motors@hotmail.com</h5>
          <h5><i class="fas fa-phone"></i> Telefone: 41 3311-1858</h5>
          <h5><i class="fab fa-whatsapp"></i> WhatsApp: 41 99753-2000</h5>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>
