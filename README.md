<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>¡Ups!</title>
  <style>
    body {
      background-color: #0f0f0f;
      color: #fff;
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    h1 {
      font-size: 3em;
      color: #ff4444;
    }
    p {
      font-size: 1.2em;
      margin-top: 20px;
      max-width: 500px;
    }
    .button {
      margin-top: 30px;
      padding: 10px 20px;
      background-color: #ff4444;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    .button:hover {
      background-color: #ff2222;
    }
  </style>
</head>
<body>
  <h1>¡Oops!</h1>
  <p>Has sido redirigido a esta página especialmente diseñada para aquellos que toman decisiones... cuestionables 😅</p>
  <button class="button" onclick="window.location.href='https://www.google.com'">Volver al mundo real</button>
</body>
</html>
