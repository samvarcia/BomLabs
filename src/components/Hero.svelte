<script>
  let HeroIlustration = "images/HeroIllustration.svg";
  let Draw1 = "images/HeroDraw.svg";
</script>

<style>
  .Hero-container {
    padding: 20px 30px;
    /* height: 80vh; */
    /* border: 1px solid red; */
  }
  .Hero-content {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    align-items: center;
  }
  .Hero-copy h1 {
    font-size: 48px;
    font-weight: bolder;
    width: 90%;
  }
  .Hero-copy p {
    font-size: 30px;
    font-weight: lighter;
    width: 800px;
  }
  .HeroImg {
    width: 370px;
  }
  @media screen and (max-width: 768px) {
    .Hero-container {
      padding: 5px 20px;
    }
    .Hero-copy h1 {
      font-size: 35px;
      width: 100%;
    }
    .Hero-copy p {
      font-size: 20px;
      width: 100%;
    }
  }
</style>

<div class="Hero">
  <div class="Hero-container">
    <div class="Hero-content">
      <div class="Hero-copy">
        <h1>Apps para estar bien, por dentro y por fuera</h1>
        <p>
          Somos la
          <b>incubadora</b>
          de apps enfocada en optimizar tus procesos del dia a dia para tener
          una vida mejor. En nuestra fase inicial lanzaremos dos aplicaciones:
          Nutracle y rouk
        </p>
      </div>
      <img class="HeroImg" src={HeroIlustration} alt="" />
    </div>
  </div>
</div>
