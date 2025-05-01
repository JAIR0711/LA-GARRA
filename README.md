<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Menú - LA GARRA</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #FF8C00);
    }

    header {
      background: linear-gradient(to bottom, #000000, #FF8C00);
      color: white;
      padding: 2em 1em;
    }

    header img {
      max-width: 200px;
      height: auto;
      margin-bottom: 1em;
    }

    .menu {
      max-width: 800px;
      margin: 20px auto;
      padding: 0 20px;
    }

    .item {
      background-color: #fff;
      border-radius: 10px;
      padding: 1em;
      margin-bottom: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .item h2 {
      margin: 0 0 5px;
    }

    .price {
      color: #FF8C00;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://media.discordapp.net/attachments/1315151875624009729/1363426460655943771/imagen_2025-04-20_020917230-removebg-preview.png?ex=6805fd57&is=6804abd7&hm=6ffcca479d67d0e429d797603b1b3260cfd9b92cfac76d845d24665dff8ac0ce&=&format=webp&quality=lossless" alt="Logo LA GARRA" />
    <h1>🍔 LA GARRA</h1>
    <p>¡Nuestro delicioso menú!</p>
  </header>

  <div class="menu">
    <div class="item">
      <h2>CHILI DE POLLO</h2>
      <p>Hamburguesa de pollo con huevo, papas, lechuga, tomate y cremas a elegir.</p>
      <p class="price">S/ 5.00</p>
    </div>
    <div class="item">
      <h2>CHILI DE CARNE</h2>
      <p>Hamburguesa de carne con queso, papa, lechuga, tomate y cremas a elegir.</p>
      <p class="price">S/ 5.00</p>
    </div>
    <div class="item">
      <h2>MAX</h2>
      <p>Una hamburguesa con carne/pollo con huevo, chorizo, queso, papa, lechuga, tomate y cremas a elegir.</p>
      <p class="price">S/ 6.00</p>
    </div>
    <div class="item">
      <h2>CHAX</h2>
      <p>La más intensa: Una hamburguesa con carne/pollo, huevo, chorizo, queso, papa, lechuga, tomate y cremas a elegir.</p>
      <p class="price">S/ 7.00</p>
    </div>
  </div>
</body>
</html>
