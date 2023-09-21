<section>
  <h2>CENTRO DE INVESTIGACIÓN Y DESARROLLO TECNOLÓGICO UNIFRANZ</h2>
  <h1>CIDTEC UNIFRANZ</h1>
  <div>
    <h3>DESARROLLO</h3>
    <h3>PROGRESO</h3>
    <h3>TECNOLOGÍA</h3>
  </div>
</section>

<style>
  section {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: var(--white);
    padding-top: 32vh;
    position: relative;
  }
  h2 {
    font-size: 16px;
    letter-spacing: 8px;
    margin-bottom: 72px;
    font-weight: 400;
    animation: aparecer 3s forwards;
    animation-delay: 800ms;
    opacity: 0;
    text-align: center;
  }
  h1 {
    font-size: 96px;
    letter-spacing: 18px;
    font-weight: 400;
    animation: aparecer 3s forwards;
    animation-delay: 300ms;
    opacity: 0;
    text-align: center;
  }
  div {
    display: flex;
    gap: 56px;
    animation: aparecer 2s forwards;
    animation-delay: 800ms;
    opacity: 0;
  }
  h3 {
    font-size: 12px;
    letter-spacing: 6px;
    font-weight: 400;
  }

  @keyframes aparecer {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>