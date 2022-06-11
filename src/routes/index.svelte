<main>
  <header>
    <h1 class="header-text">404 not found</h1>
  </header>
  <section class="grid">
    <img src="Scarecrow.png" alt="crow" />
    <div class="info">
      <h1 class="info-header">I have bad news for you</h1>
      <p class="info-text">
        The page you are looking for might be removed or is temporarily
        unavailable
      </p>
      <button type="button" class="back-button">Back to homepage</button>
    </div>
  </section>

  <footer>
    <p class="footer-text">created by Luben Gonsalves - devChallenges.io</p>
  </footer>
</main>

<style>
  main {
    padding: 24px 40px;
  }

  .header-text {
    font-family: "Inconsolata";
    font-weight: 700;
    font-size: 2.4rem;
    text-transform: uppercase;
    color: #333333;
    margin-bottom: 20rem;
  }

  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 100px;
  }

  .info-header {
    font-family: "Space Mono";
    font-weight: 700;
    font-size: 6.4rem;
    margin-bottom: 3.6rem;
  }

  .info-text {
    font-family: "Space Mono";
    font-weight: 400;
    font-size: 2.4rem;
    margin-bottom: 6.4rem;
  }

  .back-button {
    padding: 24px;
    font-family: "Space Mono";
    font-weight: 700;
    font-size: 14px;
    background: #333333;
    width: 216px;
    height: 68px;
    color: #ffffff;
    cursor: pointer;
  }

  .footer-text {
    font-family: "Montserrat";
    position: fixed;
    transform: translateX(-50%);
    bottom: 24px;
    left: 50%;
    font-weight: 500;
    font-size: 1.6rem;
    color: #bdbdbd;
  }

  @media only screen and (max-width: 768px) {
    .grid {
      grid-template-columns: 1fr;
    }
  }
</style>
