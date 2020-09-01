<script>
  let facebook = "images/facebook.svg";
  let twitter = "images/twitter.svg";
  let instagram = "images/instagram.svg";
</script>

<style>
  .footer-container {
    padding: 40px;
  }
  .footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }
  ul {
    list-style: none;
    display: flex;
  }
  ul img {
    width: 70px;
  }
  @media screen and (max-width: 768px) {
    .footer-content {
      flex-direction: column;
    }
    ul {
      padding: 0;
    }
  }
</style>

<div class="Footer">
  <div class="footer-container">
    <div class="footer-content">
      <h1>Contacto</h1>
      <ul>
        <li>
          <img src={twitter} alt="BomLabs Twitter" />
        </li>
        <li>
          <img src={facebook} alt="Facebook" />
        </li>
        <li>
          <img src={instagram} alt="Instagram" />
        </li>
      </ul>
    </div>
  </div>
</div>
