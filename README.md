<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Aspiring Java Dev</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      height: 100vh;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      overflow: hidden;
    }

    .card {
      text-align: center;
      padding: 50px 70px;
      border-radius: 20px;
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(10px);
      box-shadow: 0 0 40px rgba(0, 0, 0, 0.4);
      animation: float 4s ease-in-out infinite;
    }

    h1 {
      font-size: 3rem;
      font-weight: 700;
      letter-spacing: 2px;
      animation: slideDown 1.2s ease forwards;
    }

    .typing {
      margin-top: 15px;
      font-size: 1.5rem;
      font-weight: 300;
      color: #00ffcc;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #00ffcc;
      width: 0;
      animation: typing 3s steps(20) forwards, blink 0.7s infinite;
    }

    .tags {
      margin-top: 30px;
      display: flex;
      gap: 12px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .tag {
      padding: 8px 16px;
      border-radius: 50px;
      font-size: 0.9rem;
      background: rgba(0, 255, 204, 0.15);
      color: #00ffcc;
      animation: fadeUp 1.5s ease forwards;
    }

    /* Animations */
    @keyframes typing {
      from { width: 0 }
      to { width: 220px }
    }

    @keyframes blink {
      50% { border-color: transparent }
    }

    @keyframes slideDown {
      from {
        opacity: 0;
        transform: translateY(-40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0) }
      50% { transform: translateY(-12px) }
    }
  </style>
</head>

<body>
  <div class="card">
    <h1>👋 Hi, I'm Sumant</h1>
    <div class="typing">Aspiring Java Dev</div>

    <div class="tags">
      <div class="tag">Java</div>
      <div class="tag">OOP</div>
      <div class="tag">DSA</div>
      <div class="tag">Spring (Learning)</div>
      <div class="tag">Backend</div>
    </div>
  </div>
</body>
</html>

