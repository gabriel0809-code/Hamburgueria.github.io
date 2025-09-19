# Hamburgueria.github.io
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hamburgueria PPL</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #f5f5f5;
    }
    header {
      background-color: #222;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #ffcc00;
    }
    nav {
      background-color: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #f5f5f5;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffcc00;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    .cardapio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .burger {
      background-color: #222;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
    .burger img {
      max-width: 100%;
      border-radius: 10px;
    }
    .burger h3 {
      color: #ffcc00;
      margin: 15px 0 5px;
    }
    footer {
      background-color: #222;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #ffcc00;
      color: #111;
      font-weight: bold;
      border-radius: 5px;
      text-decoration: none;
    }
    .btn:hover {
      background-color: #ffaa00;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hamburgueria PPL </h1>
    <p>O melhor burger artesanal da cidade 🍔🔥</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#cardapio">Cardápio</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="home">
    <h2>Bem-vindo!</h2>
    <p>Aqui você encontra hambúrgueres artesanais preparados na chapa, com ingredientes  selecionados. Experimente nossas combinações exclusivas e descubra o verdadeiro gosto do burger artesanal perfeito!</p>
  </section>

  <section id="cardapio">
    <h2>Cardápio</h2>
    <div class="cardapio">
      <div class="burger">
        <img src="https://via.placeholder.com/300x200.png?text=Cheeseburger" alt="Cheeseburger">
        <h3>Cheeseburger</h3>
        <p>Pão brioche, hambúrguer 180g, queijo cheddar, alface e tomate.</p>
        <strong>R$ 25,00</strong>
      </div>
      <div class="burger">
        <img src="https://via.placeholder.com/300x200.png?text=Bacon+Burger" alt="Bacon Burger">
        <h3>Bacon Burger</h3>
        <p>Pão brioche, hambúrguer 180g, cheddar, bacon crocante e molho da casa.</p>
        <strong>R$ 32,00</strong>
      </div>
      <div class="burger">
        <img src="https://via.placeholder.com/300x200.png?text=Veggie+Burger" alt="Veggie Burger">
        <h3>Veggie Burger</h3>
        <p>Pão integral, hambúrguer de grão-de-bico, rúcula, tomate seco e maionese vegana.</p>
        <strong>R$ 28,00</strong>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Fundada em 2025, a <strong>Hamburgueria PPL </strong> nasceu da paixão por churrasco e comida de qualidade. Nossa missão é trazer experiências únicas em cada mordida.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>📍 Endereço: Rua dos Sabores, 123 - Centro</p>
    <p>📞 Telefone: (15) 99163-7679</p>
    <p>📱 WhatsApp: <a class="btn" href="https://wa.me/5515991637679" target="_blank">Peça Agora</a></p>
  </section>

  <footer>
    <p>🍔 Hamburgueria PPL - Todos os direitos reservados - 2025</p>
  </footer>
</body>
</html>
