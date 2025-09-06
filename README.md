<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apresentação</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #1e1e2f, #2a2a40, #0f172a);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      overflow: hidden;
    }

    .container {
      text-align: center;
    }

    .welcome {
      font-size: 2.2rem;
      color: #d1d5db;
      margin-bottom: 15px;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
    }

    .name {
      font-size: 3rem;
      font-weight: bold;
      background: linear-gradient(90deg, #60a5fa, #34d399, #facc15, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      white-space: nowrap; /* nunca quebra o nome */
      overflow: visible; /* garante que não corte */
      opacity: 0;
      transform: translateY(40px);
      animation: fadeInUp 1.5s ease forwards;
      animation-delay: 1s;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.4);
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* efeito no hover */
    .name:hover {
      filter: brightness(1.2);
      transform: scale(1.05);
      transition: 0.4s ease;
    }

    /* responsividade */
    @media (max-width: 600px) {
      .welcome {
        font-size: 1.6rem;
      }
      .name {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="welcome">Olá, seja bem-vindo!</div>
    <div class="name">Carlos Henrique</div>
  </div>
</body>
</html>
