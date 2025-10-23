<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Pendaftaran Jadi Pacar 💘 + Tes Kecocokan</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive;
      background-color: #ffe6f2;
      text-align: center;
      padding: 40px;
      overflow-x: hidden;
      color: #333;
    }

    h1 {
      color: #ff3385;
      text-shadow: 1px 1px #fff;
    }

    form {
      background-color: #fff;
      display: inline-block;
      padding: 20px 30px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(255, 51, 133, 0.3);
      margin-top: 20px;
    }

    input, select, textarea, button {
      display: block;
      margin: 10px auto;
      padding: 10px;
      width: 80%;
      border: 2px solid #ff80aa;
      border-radius: 10px;
      font-size: 14px;
    }

    button {
      background-color: #ff3385;
      color: white;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    button:hover {
      background-color: #ff66a3;
      transform: scale(1.05);
    }

    .result {
      margin-top: 30px;
      background: #fff;
      padding: 20px;
      display: inline-block;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(255, 51, 133, 0.2);
      animation: fadeIn 0.8s ease;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    .heart {
      position: fixed;
      bottom: 0;
      color: #ff6699;
      font-size: 20px;
      animation: floatUp 4s linear infinite;
      opacity: 0.8;
    }

    @keyframes floatUp {
      0% {
        transform: translateY(0) scale(1);
        opacity: 0.8;
      }
      100% {
        transform: translateY(-800px) scale(1.5);
        opacity: 0;
      }
    }

    .footer {
      margin-top: 30px;
      font-size: 13px;
      color: #666;
    }
  </style>
</head>
<body>
  <h1>💖 Form Pendaftaran Jadi Pacar 💖</h1>
  <p>maap yang bikin juga geli sebenernyaa 😍</p>

  <form id="loveForm">
    <input type="text" id="nama" placeholder="Nama kamu 😚" required>
    <input type="number" id="umur" placeholder="Umur kamu 💕" required>
    <select id="status" required>
      <option value="">Status kamu sekarang 💔</option>
      <option value="single">Single (lagi nunggu kamu 😳)</option>
      <option value="complicated">It's complicated 😅</option>
      <option value="taken">Udah ada tapi bisa ditinggal 😏</option>
    </select>
    <textarea id="alasan" placeholder="Kenapa pengen jadi pacar aku? 😍" required></textarea>
    <textarea id="kenapa_dipilih" placeholder="Kenapa aku harus pilih kamu? 💕" required></textarea>
    <button type="submit">Tes Kecocokan ❤️</button>
  </form>

  <div id="result" class="result" style="display:none;"></div>

  <p class="footer">© 2025 Web Cinta Inc. | Dibuat dengan aca ❤️</p>

  <script>
    const form = document.getElementById("loveForm");
    const resultBox = document.getElementById("result");

    form.addEventListener("submit", function(e) {
      e.preventDefault();
      const nama = document.getElementById("nama").value;
      const umur = document.getElementById("umur").value;
      const alasan = document.getElementById("alasan").value;
      const kenapa = document.getElementById("kenapa_dipilih").value;

      // Bikin efek hati
      for (let i = 0; i < 15; i++) {
        const heart = document.createElement("div");
        heart.classList.add("heart");
        heart.innerHTML = "💖";
        heart.style.left = Math.random() * 100 + "vw";
        heart.style.animationDuration = (3 + Math.random() * 2) + "s";
        document.body.appendChild(heart);
        setTimeout(() => heart.remove(), 4000);
      }

      // Hitung skor kecocokan random
      let score = Math.floor(Math.random() * 41) + 60; // 60-100%
      let message = "";

      if (score >= 90) {
        message = "Waduh, kita cocok banget! 🥰 Langsung siapin tanggal, yuk!";
      } else if (score >= 80) {
        message = "Lumayan cocok nih 😳 masih bisa diperjuangkan 💞";
      } else {
        message = "Masih bisa, asal kamu janji gak PHP ya 😅";
      }

      // Tampilkan hasil
      resultBox.style.display = "block";
      resultBox.innerHTML = `
        <h2>💌 Hai ${nama}!</h2>
        <p>Hasil tes kecocokan cinta kamu adalah:</p>
        <h1>${score}% 💘</h1>
        <p>${message}</p>
        <hr>
      `;

      // Reset form
      form.reset();
    });
  </script>
</body>
</html>
# aca
