<template>
  <div>
    <section class="hero is-medium is-orange is-bold has-text-centered">
      <div class="hero-body">
        <img src="logo.svg" alt="JustShip" width="100pt" class="brand" />

        <p class="title has-text-white">
          JustShip
        </p>

        <div class="columns is-centered">
          <div class="column is-narrow">
            <p class="description has-text-white">
              Un espacio para ayudar a devs, makers y hackers a recorrer el camino y <b>simplemente lanzar</b>.
            </p>
            <b-field>
              <b-input placeholder="elon@tesla.com" rounded />
              <p class="control">
                <b-button type="is-warning" icon-left="email" rounded>
                  Suscribirme
                </b-button>
              </p>
            </b-field>
          </div>
        </div>
      </div>
    </section>

    <!-- post -->
    <section class="section">
      <h1 class="title has-text-centered" style="margin-bottom: 30pt;">
        Comunidad de creativos
      </h1>
      <div class="post">
        <div class="columns is-centered">
          <div class="column is-narrow">
            <img
              src="https://miro.medium.com/max/1400/0*486qAjHvt7abHeGI"
              alt="De la idea al producto: JustShip."
              class="post-cover"
            />
          </div>
          <div class="column is-3 is-12-mobile">
            <div class="media post-author">
              <div class="media-left">
                <img
                  src="https://miro.medium.com/fit/c/96/96/1*i4BcOt_ZAjUhi6W5aQN6dQ.jpeg"
                  alt="Carlos Lugones"
                  class="avatar"
                />
              </div>
              <div class="media-content">
                <p>Carlos Lugones</p>
                <p class="post-time">
                  <small>Sep 19 · 6 minutos</small>
                </p>
              </div>
            </div>
            <p class="post-description">
              <small>
                Como su nombre lo dice: Just ship, simplemente lánzalo. Queremos crear un club digital,
                una plataforma, que ayude a nuevos creativos a unirse al movimiento de indie makers a
                nivel mundial, ese que te permite transformar tus ideas en productos reales, y fallar
                rápido si es necesario, hasta llegar al éxito.
              </small>
            </p>
            <a href="https://medium.com/justship/de-la-idea-al-producto-justship-fd5d9fd3ae83" target="_blank">
              <b-button type="is-black" rounded>
                Leer más...
              </b-button>
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- end post -->

    <!-- features -->
    <section
      class="section image-box has-text-white"
      style="background-image: url('https://images.unsplash.com/photo-1592561199818-6b69d3d1d6e2?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1288&q=80')"
    >
      <h1 class="title has-text-white has-text-centered">
        Open source
      </h1>

      <div class="columns is-centered has-text-centered">
        <div class="column is-3 is-12-mobile">
          Nuestro objetivo es crear un espacio descentralizado, creado desde la comunidad y para la comunidad.
        </div>
      </div>

      <div class="columns is-centered">
        <div class="column is-narrow">
          <div class="feature">
            <b-icon icon="xml" />
          </div>
        </div>
        <div class="column is-2 is-12-mobile">
          Código fuente abierto
        </div>
      </div>

      <div class="columns is-centered">
        <div class="column is-narrow">
          <div class="feature">
            <b-icon icon="handshake" />
          </div>
        </div>
        <div class="column is-2 is-12-mobile">
          Colaboración abierta y pública
        </div>
      </div>

      <div class="columns is-centered">
        <div class="column is-narrow">
          <div class="feature">
            <b-icon icon="currency-usd" />
          </div>
        </div>
        <div class="column is-2 is-12-mobile">
          Administración transparente de los recursos y las finanzas
        </div>
      </div>

      <div class="columns is-centered">
        <div class="column is-narrow">
          <div class="feature">
            <b-icon icon="thumb-up" />
          </div>
        </div>
        <div class="column is-2 is-12-mobile">
          Decisiones y propiedad colectivas
        </div>
      </div>
    </section>
    <!-- end features -->

    <!-- funding -->
    <section class="section">
      <h1 class="title has-text-centered">
        Apóyanos
      </h1>

      <div class="columns is-centered has-text-centered">
        <div class="column is-3 is-12-mobile">
          Tu donación nos ayuda a materializar nuestra misión de acompañar a miles de creativos en su camino al crear startups.
        </div>
      </div>

      <p class="donations">
        <a href="https://ko-fi.com/justship" target="_blank">
          <img src="https://ko-fi.com/img/Kofi_Logo_Blue.svg" alt="QvaPay" width="90pt" />
        </a>
        <a href="https://qvapay.com/payme/justshipto" target="_blank">
          <img src="https://qvapay.com/img/logo/qvapay-logo-d.png" alt="QvaPay" width="150pt" />
        </a>
      </p>

      <div class="columns is-centered">
        <div class="column is-narrow">
          <!-- btc -->
          <div class="card wallet">
            <div class="card-content">
              <img src="/wallets/btc.png" alt="BTC" />
              <p>
                <b-icon icon="bitcoin" size="is-small" />
                BTC
              </p>
            </div>
          </div>
          <!-- end btc -->
        </div>
        <div class="column is-narrow">
          <!-- eth -->
          <div class="card wallet">
            <div class="card-content">
              <img src="/wallets/eth.png" alt="ETH" />
              <p>
                <b-icon icon="ethereum" size="is-small" />
                ETH
              </p>
            </div>
          </div>
          <!-- end eth -->
        </div>
        <div class="column is-narrow">
          <!-- litecoin -->
          <div class="card wallet">
            <div class="card-content">
              <img src="/wallets/litecoin.png" alt="Litecoin" />
              <p>
                <b-icon icon="litecoin" size="is-small" />
                Litecoin
              </p>
            </div>
          </div>
          <!-- end litecoin -->
        </div>
        <div class="column is-narrow">
          <!-- usdt -->
          <div class="card wallet">
            <div class="card-content">
              <img src="/wallets/usdt.png" alt="USDT" />
              <p>Tether USDT TRC20</p>
            </div>
          </div>
          <!-- end usdt -->
        </div>
        <div class="column is-narrow">
          <!-- matic -->
          <div class="card wallet">
            <div class="card-content">
              <img src="/wallets/matic.png" alt="Matic" />
              <p>Matic</p>
            </div>
          </div>
          <!-- end matic -->
        </div>
      </div>
    </section>
    <!-- end funding -->

    <!-- footer -->
    <section class="section bfooter">
      <a href="https://twitter.com/JustShipTo" class="social">
        <b-icon icon="twitter" size="is-medium" />
      </a>
      <a href="https://t.me/JustShipTo" class="social">
        <b-icon icon="telegram" size="is-medium" />
      </a>
      <a href="https://linkedin.com/company/justshipto" class="social">
        <b-icon icon="linkedin" size="is-medium" />
      </a>
      <a href="https://github.com/JustShip" class="social">
        <b-icon icon="github" size="is-medium" />
      </a>
      <a href="mailto:justshipto@gmail.com" class="social">
        <b-icon icon="email" size="is-medium" />
      </a>
    </section>
    <!-- end footer -->
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.is-orange {
  background-size: cover;
  background-image: url('https://images.unsplash.com/photo-1457365050282-c53d772ef8b2?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=80');
}
.brand {}
.description {
  width: 300pt;
  margin: 20pt 0 30pt 0;
}

/* Post */
.post {}
.post .post-cover {
  width: 300pt;
  border-radius: 10pt;
}
.post .post-author {
  margin-bottom: 10pt;
}
.post .post-author .avatar {
  width: 40pt;
  border-radius: 50%;
}
.post .post-time {
  color: gray;
}
.post .post-description {
  margin-bottom: 10pt;
}

.feature {
  width: 37pt;
  height: 37pt;
  padding: 10pt;
  background-color: #4361ee;
  border-radius: 50%;
  text-align: center;
}

.donations {
  text-align: center;
}
.donations a {
  color: #4361ee;
}

.donations a:not(:last-child){
  margin-right: 10pt;
}

.wallet {
  text-align: center;
  display: inline-block;
  margin: 0 10pt 0 10pt;
}
.wallet img {
  width: 130pt;
}

.bfooter {
  text-align: center;
  background-color: #10002b;
}
.bfooter a {
  color: white;
}
.bfooter .social {
  margin-right: 15pt;
}
.bfooter .social:last-child {
  margin-right: 0;
}

.image-box {
  box-shadow: inset 0 0 0 100vw rgba(0,0,0,0.5);
  background-size: cover;
}
</style>
