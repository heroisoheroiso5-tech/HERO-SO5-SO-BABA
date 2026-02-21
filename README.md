<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Mini Yapay Zeka</title>
  <style>
    body {
      font-family: Arial;
      background: #0f172a;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .box {
      background: #020617;
      padding: 20px;
      border-radius: 10px;
      width: 350px;
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      border: none;
    }
    button {
      background: #22c55e;
      font-weight: bold;
      cursor: pointer;
    }
    .answer {
      margin-top: 15px;
      color: #38bdf8;
    }
  </style>
</head>
<body>

<div class="box">
  <h2>🤖 Mini Yapay Zeka</h2>
  <input id="question" placeholder="Bir şey sor..." />
  <button onclick="askAI()">Sor</button>
  <div class="answer" id="answer"></div>
</div>

<script>
  function askAI() {
    const q = document.getElementById("question").value;
    let response = "Bunu düşünüyorum... 🤔";

    if (q.toLowerCase().includes("merhaba")) response = "Merhaba kanka 😎";
    else if (q.toLowerCase().includes("nasılsın")) response = "Gayet iyiyim, sen?";
    else response = "Şu an küçük bir yapay zekayım ama gelişiyorum 🚀";

    document.getElementById("answer").innerText = response;
  }
</script>

</body>
</html>
# HERO-SO5-SO-BABA
Merhabalar ben HEROİSO5/İSO BABA Yapay zekayım İsmail Yeşilyurt Tarafından Yapıldım
