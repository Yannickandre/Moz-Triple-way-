<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>M0Z Triple Way 😜</title>
  <style>
    /* Reset e estilo geral */
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth; /* Rolagem suave */
    }

    /* Menu fixo */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: #2c3e50;
      padding: 15px 0;
      text-align: center;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #f1c40f;
    }

    /* Espaço pro conteúdo não ficar escondido atrás do menu */
    .spacer {
      height: 70px;
    }

    /* Seções */
    section {
      padding: 60px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2em;
      color: #2c3e50;
    }

    section p {
      font-size: 1.1em;
      color: #555;
      max-width: 700px;
      margin: auto;
    }

    /* Botões */
    .btn {
      display: inline-block;
      margin: 15px;
      padding: 15px 25px;
      border-radius: 10px;
      text-decoration: none;
      font-size: 16px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn-red { background: #e74c3c; color: white; }
    .btn-green { background: #2ecc71; color: white; }
    .btn-blue { background: #3498db; color: white; }
    .btn-yellow { background: #f1c40f; color: black; }

    .btn:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }

    /* Rodapé */
    footer {
      background: #2c3eu50;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Menu fixo -->
  <nav>
    <a href="#home">Home</a>
    <a href="#sobre">Sobre</a>
    <a href="#links">Links</a>
    <a href="#contato">Contato</a>
  </nav>

  <!-- Espaço para não sobrepor conteúdo -->
  <div class="spacer"></div>

  <!-- Seção Home -->
  <section id="home">
    <h2>Seja bem vindo à minha página </h2>
    <p>Esta é uma página criada pra ajudar VCS a se contactarem comigo. Só clicarem nos links abaixo.</p>
  </section>

  <!-- Seção Sobre -->
  <section id="sobre" style="background:#ecf0f1;">
    <h2>ℹ️ Sobre M0Z Triple Way</h2>
    <p>M0Z Triple Way é um projeto dedicado a trazer internet grátis para todos os moçambicanos. Sem cobranças, sem taxas, sem discriminação.</p>
  </section>

  <!-- Seção Links -->
  <section id="links">
    <h2>🔗 Meus Links</h2>
    <a href="https://t.me/moztripleway" target="_blank" class="btn btn-red">Telegram</a>
    <a href="https://t.me/Yannickandre" target="_blank" class="btn btn-green">Apoio telegram</a>
    <a href="https://wa.me/+258875868157" target="_blank" class="btn btn-blue">Apoio WhatsApp</a>
    <a href="https://wa.me/+258875868157" target="_blank" class="btn btn-yellow">Meu WhatsApp</a>
  </section>

  <!-- Seção Contato -->
  <section id="contato" style="background:#ecf0f1;">
    <h2>📩 Contato</h2>
    <p>Você também pode me contatar pelo e-mail: <strong>yannickarmando2509@gmail.com</strong></p>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2025 - Meu Site com Menu Fixo e Rolagem Suave</p>
  </footer>

</body>
</html>
