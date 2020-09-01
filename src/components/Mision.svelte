<script>
  let bgImageMision = "images/woman-jumping-workout.jpg";
  let bgImageVision = "images/black-smartphone-displays-the-word-hello.jpg";
  let bgImageObjetivos = "images/colors-on-a-backlit-keyboard.jpg";
  import Modal from "../components/Modal.svelte";
  import Share from "../components/Share.svelte";
  let isModal = false;
  function handleClick() {
    isModal = !isModal;
  }
</script>

<style>
  .Mision-container {
    padding: 10px 60px;
    text-align: center;
  }
  .card {
    margin: 20px;
    font-size: 20px;
    border-radius: 20px;
    padding: 30px;
    color: #fff;
  }
  .mision-card {
    background-size: 100%;
  }
  button {
    color: #fff;
    font-size: 15px;
    margin-top: 15px;
    padding: 10px;
    border-radius: 20px;
    background-image: linear-gradient(to right, #4158d0, #c850c0, #ffcc70);
  }
  @media screen and (max-width: 768px) {
    .Mision-container {
      padding: 2px 10px;
    }
    .mision-card {
      background-repeat: no-repeat;
      background-size: cover;
    }
    .card {
      padding: 5px;
      margin: 5px;
    }
  }
</style>

<div class="Mision">
  {#if isModal}
    <div>
      <Modal>
        <Share on:click={handleClick} />
      </Modal>
    </div>
  {/if}
  <div class="Mision-container">
    <div class="Mision-content">
      <div
        class="mision-card card"
        style="background-image: url('{bgImageMision}')">
        <h1>Mision</h1>
        <p>
          Crecer como una empresa que da un servicio de salud de calidad,
          afectando positivamente la calidad de vida de nuestros usuarios.
        </p>
      </div>
      <div
        class="vision-card card"
        style="background-image: url('{bgImageVision}')">
        <h1>Vision</h1>
        <p>
          En 2030 ser la empresa lider en creacion de productos digitales
          enfocados en optimizar el dia a dia de nuestros usuarios
        </p>
      </div>
      <div
        class="objetivos-card card"
        style="background-image: url('{bgImageObjetivos}')">
        <h1>Objetivos</h1>
        <p>
          Desarrollar apps móviles que ayuden al mejoramiento de los hábitos
          saludables en la vida de los usuarios.
        </p>
        <h3>Objetivos especificos:</h3>
        <p>
          1. Consolidar de una red virtual como una cadena de aplicaciones
          móviles.
          <br />
          2. Desarrollar de un nuevo software con mayor utilidad en las
          funciones móviles .
        </p>
      </div>
      <button on:click={handleClick}>
        <h1>Marco Legal</h1>
      </button>

    </div>
  </div>
</div>
