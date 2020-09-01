<script>
  let nutDraw = "images/NutracleDraw.svg";
  let rouDraw = "images/RoukCover.svg";
  let store = "images/Stores.svg";
</script>

<style>
  .Nutracle {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0px 150px;
    margin-top: 20px;
    /* border: 1px solid red; */
  }
  .nut-img {
    width: 500px;
  }
  .nut-copy h1 {
    font-size: 45px;
  }
  .nut-copy p {
    font-size: 25px;
    width: 600px;
  }
  .copy-foot h2 {
    background: linear-gradient(#08aeea, #2af598);
    -webkit-background-clip: text;
    color: transparent;
  }
  .copy-foot-2 h2 {
    background: linear-gradient(#21d4fd, #b721ff);
    -webkit-background-clip: text;
    color: transparent;
  }
  a {
    text-decoration: none;
  }
</style>

<div class="Apps">
  <div class="Apps-container">
    <div class="Apps-content">
      <div class="Nutracle">
        <img class="nut-img" src={nutDraw} alt="" />
        <div class="nut-copy">
          <h1>Nutracle</h1>
          <p>
            Lleva un registro extacto sobre tu nutrición diaria. Encuentra
            recetas que se adaptan a tus gustos y necesidades
          </p>
          <div class="copy-foot">
            <img src={store} alt="Donde descargar?" />
            <a href="">
              <h2>Ver prototipo</h2>
            </a>
          </div>
        </div>
      </div>
      <div class="Nutracle">
        <div class="nut-copy">
          <h1>Rouk</h1>
          <p>
            Cada cuerpo es distinto y por eso tenemos rutinas para ti, trabaja
            diferentes grupos musculares y cumple mentas que te lleven a el
            cuerpo que deseas
          </p>
          <div class="copy-foot-2">
            <img src={store} alt="Donde descargar?" />
            <a href="">
              <h2>Ver prototipo</h2>
            </a>
          </div>
        </div>
        <img class="nut-img" src={rouDraw} alt="" />
      </div>
    </div>
  </div>
</div>
