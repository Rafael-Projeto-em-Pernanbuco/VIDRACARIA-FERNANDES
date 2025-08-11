
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vidraçaria Fernandes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f0f8ff;
      color: #000;
    }

    header {
      background-color: #003366; /* azul escuro */
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #3399ff; /* azul claro */
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 20px;
    }

    .produtos {
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      margin-top: 20px;
    }

    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }

    .whatsapp-chat {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Vidraçaria Fernandes</h1>
    <p>Rua Padre Medeiros, Nº87 - Centro, Exu-PE</p>
  </header>

  <nav>
    <a href="#produtos">Produtos</a>
    <a href="#mapa">Localização</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="produtos" class="produtos">
    <h2>Nossos Produtos</h2>
    <ul>
      <li>Box para Banheiro</li>
      <li>Espelhos</li>
      <li>Janelas</li>
      <li>Portas</li>
      <li>PVC</li>
    </ul>
  </section>

  <section id="mapa">
    <h2>Como chegar</h2>
    <iframe 
      src="https://www.google.com/maps?q=Rua+Padre+Medeiros+87,+Exu,+PE&output=embed">
    </iframe>
  </section>

  <section id="contato" class="produtos">
    <h2>Entre em Contato</h2>
    <p>Fale conosco pelo WhatsApp!</p>
    <!-- Link de exemplo, substitua o número abaixo pelo seu -->
    <a class="whatsapp-chat" href="https://wa.me/5587999999999" target="_blank">💬 WhatsApp</a>
  </section>

  <!-- Google Tradutor -->
  <div id="google_translate_element" style="position: fixed; top: 10px; right: 10px;"></div>
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({pageLanguage: 'pt', includedLanguages: 'en,es,fr,de,it'}, 'google_translate_element');
    }
  </script>
  <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <footer>
    <p>&copy; 2025 Vidraçaria Fernandes - Todos os direitos reservados.</p>
  </footer>
</body>
</html>
