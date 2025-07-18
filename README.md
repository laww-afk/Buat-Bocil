<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>I Love You Bocilll</title>
  <style>
    body {
      background: #ffd1dc;
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #ff0055;
      font-size: 3em;
    }
    #gombal {
      margin-top: 30px;
      font-size: 1.5em;
      color: #990033;
    }
    button {
      background-color: #ff69b4;
      border: none;
      color: white;
      padding: 15px 30px;
      font-size: 1em;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #ff1493;
    }
  </style>
</head>
<body>
  <h1>I Love You Bocilll 💖</h1>
  <p id="gombal">Klik tombolnya untuk digombalin 😘</p>
  <button onclick="gombal()">Gombalin Aku!</button>

  <script>
    const gombalan = [
      "Kalau kamu bintang, aku langitnya~",
      "Aku gak pandai matematika, tapi aku yakin kita berjodoh.",
      "Kamu itu ibarat kopi... bikin deg-degan tapi nagih!",
      "Aku gak minta apa-apa, cukup kamu aja yang jadi alasanku bahagia.",
      "Kalau kamu senyum, dunia jadi terang 😍"
    ];

    function gombal() {
      const random = Math.floor(Math.random() * gombalan.length);
      document.getElementById("gombal").innerText = gombalan[random];
    }
  </script>
</body>
</html>
