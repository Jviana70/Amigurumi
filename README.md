<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mimos de Fio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff8f2;
      color: #4d3e3e;
    }
    header {
      background-color: #ffb6b9;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      background-color: #ffe0e3;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4d3e3e;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .produtos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .produto {
      border: 1px solid #ffd3d6;
      border-radius: 10px;
      padding: 10px;
      width: 200px;
      text-align: center;
      background-color: #fff;
    }
    .produto img {
      max-width: 100%;
      border-radius: 8px;
    }
    footer {
      background-color: #ffb6b9;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mimos de Fio</h1>
    <p>Feitos com carinho em cada ponto de crochê ♥</p>
  </header>

  <nav>
    <a href="#produtos">Produtos</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="produtos">
    <h2>Nossos Produtos</h2>
    <div class="produtos">
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Boneca de crochê">
        <h3>Boneca Amigurumi</h3>
        <p>Feita à mão com fio 100% algodão. Aprox. 20cm.</p>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Ursinho de crochê">
        <h3>Ursinho Carinhoso</h3>
        <p>Ideal para bebês. Encomenda sob medida.</p>
      </div>
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Sapatinho de bebê">
        <h3>Sapatinhos de Bebê</h3>
        <p>Macios, confortáveis e super fofos!</p>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre</h2>
    <p>Sou Jacqueline, artesã apaixonada por crochê. Crio cada peça com amor, cuidado e dedicação, pensando no conforto e alegria de quem recebe. O "Mimos de Fio" nasceu do sonho de transformar fios em carinho. ♥</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato pelo WhatsApp: <strong>(00) 00000-0000</strong></p>
    <p>Nos siga no Instagram: <a href="#">@mimosdefio</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Mimos de Fio - Todos os direitos reservados</p>
  </footer>
</body>
</html>

