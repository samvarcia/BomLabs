<style>
  .Share {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    background-color: white;
    margin: 30px;
    width: 50%;
    height: auto;
    position: relative;
    top: 0;
    justify-self: center;
    z-index: 9;
    padding: 1em;
  }
  .Share-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Share-head h2 {
    font-size: 16px;
  }
  .Share-head p {
    cursor: pointer;
  }
  @media screen and (max-width: 768px) {
    .Share {
      width: 80%;
      margin: 20px;
    }
  }
</style>

<div class="Share">
  <div class="Share-head">
    <h2>Marco Legal</h2>
    <p on:click>Salir</p>
  </div>
  <div class="Share-content">
    <p>
      Este proyecto se realizará enmarcado bajo la Constitución Política de
      Colombia, promulgada en la Gaceta Constitucional número 144 del jueves 4
      de julio de 1991 ya que en esta se encuentra el Conpes social 113 de 2008
      que se refiere y cito: “A la disponibilidad suficiente y estable de
      alimentos, el acceso y el consumo oportuno y permanente de los mismos en
      cantidad, calidad e inocuidad por parte de todas las personas, bajo
      condiciones que permitan su adecuada utilización biológica, para llevar
      una vida saludable y activa.”
      <br />
      <br />
      También en ella se encuentra el artículo 52 el cual se refiere al derecho
      que tienen los colombianos de hacer deporte libremente: “El deporte y la
      recreación, forman parte de la educación y constituyen gasto público
      social.” Por último, en ella está inmersa la ley 11723, que contiene 89
      artículos, hablando de la regulación que se tiene por los derechos de
      propiedad de una obra artística, científica o literaria: “Cuando por Ley
      25036 se le introdujeron modificaciones referidas al software, para darle
      fin a las discusiones doctrinarias y jurisprudenciales sobre la cuestión
      de si el software estaba o no bajo el amparo de esta ley.”
    </p>
  </div>
</div>
