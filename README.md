<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Vishu | Ramiz Roshan</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #fff9e6, #fff1c1);
      text-align: center;
      padding: 2em;
      color: #333;
      background-image: url('https://i.imgur.com/BjbaHMG.png'); /* Light flower bg */
      background-size: cover;
      background-repeat: no-repeat;
    }

    .container {
      background: rgba(255, 255, 255, 0.95);
      max-width: 400px;
      margin: auto;
      padding: 2em;
      border-radius: 25px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
      position: relative;
      border: 5px solid gold;
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from { box-shadow: 0 0 10px gold; }
      to { box-shadow: 0 0 25px goldenrod; }
    }

    .profile-pic {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #ffcc00;
      margin-bottom: 1em;
    }

    .qr-code {
      width: 180px;
      border-radius: 10px;
      margin-top: 1em;
      border: 2px dashed #ffcc00;
    }

    .vishu-banner {
      font-family: 'Great Vibes', cursive;
      font-size: 1.8em;
      color: #d88a00;
      font-weight: bold;
      margin-bottom: 1em;
    }

    h2 {
      margin-top: 0;
      font-size: 1.3em;
      color: #444;
    }

    p {
      font-size: 1em;
      margin-top: 0.5em;
      color: #555;
    }

    .flowers {
      position: absolute;
      width: 30px;
      animation: float 6s infinite ease-in-out;
    }

    .flower1 { top: -10px; left: -10px; }
    .flower2 { bottom: -10px; right: -10px; }

    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(10px); }
      100% { transform: translateY(0px); }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Decorative floating flowers -->
    <img src="https://i.imgur.com/nYkUcQ3.png" class="flowers flower1" alt="flower" />
    <img src="https://i.imgur.com/nYkUcQ3.png" class="flowers flower2" alt="flower" />

    <img src=""C:\Users\EBilling\Downloads\1000172594.jpg"" alt="Ramiz Roshan" class="profile-pic" />
    <div class="vishu-banner">🌼 Happy Vishu! 🌼</div>
    <h2>Ramiz Roshan</h2>
    <img src=""C:\Users\EBilling\Downloads\GooglePay_QR.png"" alt="UPI QR Code" class="qr-code" />
    <p><strong>UPI ID:</strong> ramizroshan123@okaxis</p>
    <p>Scan to pay with any UPI app</p>
  </div>
</body>
</html>
