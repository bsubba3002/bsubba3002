<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Sparkle Text Hover</title>
<style>
  body {
    background: #111;
    color: #eee;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding: 2rem;
    text-align: center;
  }

  .sparkle-text {
    font-size: 2rem;
    position: relative;
    display: inline-block;
    cursor: pointer;
    color: #fff;
  }

  .sparkle-text:hover {
    animation: sparkle 1.5s infinite;
    color: #ffd700;
  }

  @keyframes sparkle {
    0%, 100% {
      text-shadow:
        0 0 5px #fff,
        0 0 10px #ffdd55,
        0 0 20px #ffdd55,
        0 0 30px #ffdd55,
        0 0 40px #ffdd55;
    }
    50% {
      text-shadow:
        0 0 10px #fff,
        0 0 20px #ffdd55,
        0 0 30px #ffdd55,
        0 0 40px #ffdd55,
        0 0 50px #ffdd55;
    }
  }
</style>
</head>
<body>

<h1 class="sparkle-text">
  👋 Hey there, I'm <strong>Balasubrahmanya</strong>! 💻⚡<br><br>

  ✨ Exploring the future with:<br>
  🤖 AI | 📊 ML | 🎨 Generative AI | 🧠 LLMs | 🌐 Web Dev | 🕶️ AR/VR | 📋 Project Management<br><br>

  🧑‍💻 Just a human training machines to think.
</h1>

</body>
</html>
