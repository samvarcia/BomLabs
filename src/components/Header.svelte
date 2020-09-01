<script>
  let BomLogo = "images/BomLabsLogo.svg";
</script>

<style>
  .Header-container {
    padding: 0 30px;
    text-align: center;
  }
  .Header-content {
    /* display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap; */
    text-align: center;
  }
  .Header-content img {
    width: 200px;
  }
  .Header-content ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
  }
  .Header-content a {
    text-decoration: none;
    font-size: 20px;
    padding: 0 15px;
    color: #000;
    font-weight: 500;
  }
</style>

<div class="Header">
  <div class="Header-container">
    <div class="Header-content">
      <img src={BomLogo} alt="BomLabs" />
      <!-- <nav>
        <ul>
          <li>
            <a href="">Apps</a>
          </li>
          <li>
            <a href="">Mision</a>
          </li>
          <li>
            <a href="">Contacto</a>
          </li>
        </ul>
      </nav> -->
    </div>
  </div>
</div>
