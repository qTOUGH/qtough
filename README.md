<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Live Stream</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: white;
      text-align: center;
    }

    header {
      padding: 20px;
      font-size: 24px;
      font-weight: bold;
      background: #181818;
    }

    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 10px;
    }

    .stream {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
    }

    .stream iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .links {
      margin-top: 20px;
    }

    .btn {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      background: #ff3d00;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.2s;
    }

    .btn:hover {
      background: #ff5a1f;
    }

    footer {
      margin-top: 40px;
      padding: 20px;
      font-size: 12px;
      color: #aaa;
    }
  </style>
</head>

<body>

<header>
  🔴 LIVE STREAM
</header>

<div class="container">

  <!-- СТРИМ -->
  <div class="stream">
    <!-- ЗАМЕНИ channel или video -->
    <iframe
      src="https://player.twitch.tv/?channel=YOUR_CHANNEL_NAME&parent=localhost"
      allowfullscreen>
    </iframe>
  </div>

  <!-- ССЫЛКИ -->
  <div class="links">
    <a class="btn" href="https://twitch.tv/YOUR_CHANNEL_NAME" target="_blank">Twitch</a>
    <a class="btn" href="https://youtube.com" target="_blank">YouTube</a>
    <a class="btn" href="https://discord.gg" target="_blank">Discord</a>
  </div>

</div>

<footer>
  © 2026 Live Stream Page
</footer>

</body>
</html>
