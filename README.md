<div class="cards">
  <div class="card web">
    <h2>🌐 Web Developer</h2>
    <p>HTML, CSS, JS e UI/UX com foco em sites modernos.</p>
  </div>

  <div class="card app">
    <h2>📱 App Developer</h2>
    <p>Criação de apps com Flutter direto no Termux.</p>
  </div>
</div>

<style>
  .cards {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    justify-content: center;
    font-family: sans-serif;
  }
  .card {
    width: 280px;
    padding: 1rem;
    border-radius: 12px;
    box-shadow: 0 0 10px #0001;
    transition: 0.3s ease;
  }
  .card:hover {
    transform: scale(1.05);
  }
  .web {
    background: #e0f7fa;
    border-left: 5px solid #00acc1;
  }
  .app {
    background: #fce4ec;
    border-left: 5px solid #ec407a;
  }
</style>
