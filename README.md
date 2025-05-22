<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lottus Marketing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #2c2c2c;
    }
    header {
      background: #5e2d79;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      width: 100px;
      margin-bottom: 10px;
    }
    nav {
      background: #8243a7;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: linear-gradient(to right, #8243a7, #5e2d79);
      color: white;
      text-align: center;
      padding: 60px 20px;
      background-image: url('https://images.unsplash.com/photo-1599940824391-43c2d8f6c1b3');
      background-size: cover;
      background-position: center;
    }
    .hero h2 {
      margin-bottom: 10px;
      text-shadow: 1px 1px 3px #00000077;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 20px;
      max-width: 300px;
      flex: 1 1 250px;
      transition: transform 0.3s;
      color: #333;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }
    footer {
      background: #5e2d79;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: #8243a7;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://via.placeholder.com/100x100.png?text=Lottus" alt="Logo Lottus Marketing">
    <h1>Lottus Marketing</h1>
    <p>Ideias que florescem em arte</p>
  </header>

  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="hero">
    <h2>Transformamos suas ideias em artes digitais</h2>
    <p>Posts, banners, folders, cartões de visita e muito mais!</p>
    <a href="#contato" class="btn">Fale com a gente</a>
  </section>

  <section class="section" id="servicos">
    <h2>Serviços</h2>
    <div class="services">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581093588401-7f66ed5d7b4c" alt="Posts para redes">
        <h3>Posts para Redes</h3>
        <p>Artes criativas para Instagram, Facebook e outras redes sociais.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1601987077223-cfbdee5f5c81" alt="Cartões de visita">
        <h3>Cartões de Visita</h3>
        <p>Design moderno e profissional para destacar sua marca.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1587613991373-13d39aa2cd4b" alt="Folders e banners">
        <h3>Folders e Banners</h3>
        <p>Materiais digitais para campanhas, eventos e promoções.</p>
      </div>
    </div>
  </section>

  <section class="section" id="sobre">
    <h2>Sobre a Lottus</h2>
    <p>Somos especialistas em criar artes visuais digitais com identidade, criatividade e agilidade. Atendemos online com foco em entregar soluções sob medida para você e seu negócio.</p>
    <img src="https://images.unsplash.com/photo-1628691306744-c99ec4d75e3d" alt="Flor de Lótus criativa" style="width: 100%; max-width: 800px; border-radius: 10px; margin-top: 30px;">
  </section>

  <section class="section" id="contato">
    <h2>Contato</h2>
    <p>Entre em contato pelo WhatsApp:</p>
    <a href="https://wa.me/5541995315144" class="btn">(41) 99531-5144</a>
  </section>

  <footer>
    <p>&copy; 2025 Lottus Marketing. Todos os direitos reservados.</p>
    <p><a href="https://pages.github.com" style="color: white; text-decoration: underline;">Hospede seu site gratuitamente com GitHub Pages</a></p>
  </footer>
</body>
</html>
