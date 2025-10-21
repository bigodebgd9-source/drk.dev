<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abrir App moniteFF</title>

  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      text-align: center;
      padding-top: 100px;
      margin: 0;
    }

    a {
      display: inline-block;
      padding: 14px 28px;
      background-color: #007AFF;
      color: white;
      border-radius: 10px;
      text-decoration: none;
      font-size: 18px;
    }

    small {
      display: block;
      margin-top: 20px;
      color: #666;
    }
  </style>

  <script>
    function abrirApp() {
      window.location.href = "moniteFF://";
      setTimeout(() => {
        document.getElementById('fallback').style.display = 'block';
      }, 2000);
    }

    window.onload = abrirApp;
  </script>
</head>
<body>
  <h2>Abrir App moniteFF</h2>
  <p>Estamos tentando abrir o app automaticamente...</p>

  <div id="fallback" style="display:none;">
    <p>Se o aplicativo não abrir, toque no botão abaixo:</p>
    <a href="moniteFF://">Abrir moniteFF</a>
    <small>Certifique-se de que o app está instalado no dispositivo.</small>
  </div>
</body>
</html>
