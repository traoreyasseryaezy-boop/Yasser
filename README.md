
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yasser - Réseaux</title>
  <style>
    * { box-sizing: border-box; margin:0; padding:0; }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg,#0f0021,#4513a3);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .card {
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(10px);
      width: 100%;
      max-width: 420px;
      padding: 60px 25px 30px 25px;
      border-radius: 20px;
      text-align: center;
      border: 1px solid rgba(255,255,255,0.2);
      box-shadow:0 8px 20px rgba(0,0,0,0.3);
      position: relative;
    }

    .circle-name {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 auto;
      font-size: 18px;
      font-weight: bold;
      text-align: center;
      background: rgba(255,255,255,0.05);
      color: #fff;
      position: relative;
    }

    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #fff;
      object-fit: cover;
      position: absolute;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      background: #0f0021;
    }

    h1 { font-size: 26px; font-weight:700; margin:20px 0 5px 0; }
    p { font-size: 14px; opacity:0.9; margin-bottom:25px; }

    .btn {
      display:block;
      width:100%;
      padding:15px;
      margin:10px 0;
      background:#fff;
      color:#1a003d;
      font-size:17px;
      font-weight:bold;
      border-radius:14px;
      text-decoration:none;
      transition:0.25s;
    }
    .btn:hover {
      background:#ffcd47;
      color:#000;
      transform: translateY(-3px);
      box-shadow:0 4px 10px rgba(0,0,0,0.3);
    }

    @media(max-width:350px){
      h1{font-size:22px;}
      .btn{font-size:15px;padding:13px;}
      .circle-name{width:120px;height:120px;font-size:16px;}
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="circle-name">
      Yasser Trs✪
    </div>

    <h1>Yasser</h1>
    <p>Retrouve-moi ici 👇</p>

    <a class="btn" href="https://www.facebook.com/share/1CxNTA2fJz/" target="_blank">Facebook</a>
    <a class="btn" href="https://www.youtube.com/@Yasser_Trs" target="_blank">YouTube</a>
    <a class="btn" href="https://www.tiktok.com/@yasser.trs8?_r=1&_t=ZP-91rrpiiIqUR" target="_blank">TikTok</a>
    <a class="btn" href="https://www.instagram.com/yassertrs8?igsh=MXV2Z2lsanY5dHM3eg==" target="_blank">Instagram</a>
    <a class="btn" href="https://wa.me/22654962377" target="_blank">WhatsApp</a>

  </div>

</body>
</html>
