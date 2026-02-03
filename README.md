<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para Alejandra 💜</title>

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    :root{
      --morado:#6a0dad;
      --morado-suave:#b98cff;
      --fondo:#120018;
    }

    *{box-sizing:border-box}

    body{
      margin:0;
      min-height:100vh;
      background:radial-gradient(circle at top, #2a0036, var(--fondo));
      font-family:'Poppins',sans-serif;
      color:#fff;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:20px;
    }

    .card{
      max-width:420px;
      width:100%;
      padding:30px 26px 36px;
      background:linear-gradient(180deg, rgba(255,255,255,.08), rgba(255,255,255,.02));
      border-radius:26px;
      box-shadow:0 30px 80px rgba(106,13,173,.45);
      text-align:center;
      animation:fadeIn 1.4s ease;
    }

    h1{
      font-family:'Playfair Display',serif;
      font-size:2.3em;
      margin:0 0 6px;
      color:var(--morado-suave);
    }

    .subtitle{
      font-size:1.05em;
      opacity:.9;
      margin-bottom:18px;
    }

    .heart{
      font-size:44px;
      animation:pulse 1.5s infinite;
      margin:8px 0 18px;
    }

    .photo{
      margin:16px auto 22px;
      width:220px;
      border-radius:22px;
      overflow:hidden;
      box-shadow:0 18px 40px rgba(185,140,255,.6);
    }

    .photo img{
      width:100%;
      display:block;
    }

    p{
      line-height:1.6;
      font-size:1em;
      margin:12px 0;
    }

    .final{
      margin-top:18px;
      font-size:1.05em;
      color:#e6d9ff;
    }

    .names{
      margin-top:12px;
      font-weight:500;
      letter-spacing:.5px;
    }

    button{
      margin-top:26px;
      padding:14px 28px;
      border:none;
      border-radius:40px;
      background:linear-gradient(135deg, var(--morado), var(--morado-suave));
      color:white;
      font-size:1em;
      cursor:pointer;
      box-shadow:0 14px 32px rgba(185,140,255,.6);
      transition:transform .2s ease, box-shadow .2s ease;
    }

    button:hover{
      transform:translateY(-2px) scale(1.04);
      box-shadow:0 20px 44px rgba(185,140,255,.8);
    }

    footer{
      margin-top:18px;
      font-size:.75em;
      opacity:.6;
    }

    @keyframes pulse{
      0%{transform:scale(1)}
      50%{transform:scale(1.15)}
      100%{transform:scale(1)}
    }

    @keyframes fadeIn{
      from{opacity:0; transform:translateY(20px)}
      to{opacity:1; transform:translateY(0)}
    }
  </style>
</head>

<body>
  <div class="card">
    <h1>Alejandra 💜</h1>
    <div class="subtitle">Mi mami shula, mi mujer hermosa</div>

    <div class="heart">💜</div>

    <div class="photo">
      <img src="https://drive.google.com/uc?export=view&id=1cNdEHBPf3QkQydOzr9SiTmCDPnUUB89r" alt="Alejandra">
    </div>

    <p>
      No sabía cómo explicarte todo lo que siento,
      así que decidí hacerlo a mi manera.
    </p>

    <p>
      Tú eres mi cosa divina, mi crucrichus,
      la que le da sentido a mis días
      y calma mi mundo.
    </p>

    <p>
      Te amo muchísimo,
      más de lo que estas palabras pueden decir.
    </p>

    <div class="final">
      Gracias por existir, Alejandra.<br>
      Te amo.
    </div>

    <div class="names">— Yendry ✨</div>

    <button onclick="window.open('https://youtu.be/Apl-NOfMxC8?si=SnKssy6O2SXN_FHR','_blank')">
      🎶 Nuestra canción
    </button>

    <footer>
      Hecho con amor, solo para ti 💜
    </footer>
  </div>
</body>
</html>
