<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HSC পাঠ্যপুস্তক সমগ্র</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, "Noto Sans Bengali", sans-serif;
      background: linear-gradient(135deg, #0f172a, #172554, #0f172a);
      color: white;
      min-height: 100vh;
      padding: 20px;
    }
    header {
      text-align: center;
      padding: 40px 10px;
    }
    header h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }
    header p {
      color: #94a3b8;
      font-size: 16px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding-bottom: 40px;
    }
    .card {
      background: rgba(30, 41, 59, 0.96);
      border: 1px solid #334155;
      border-radius: 18px;
      padding: 25px;
      text-align: center;
      text-decoration: none;
      color: white;
      transition: 0.3s;
    }
    .card:hover {
      border-color: #3b82f6;
      transform: translateY(-5px);
    }
    .card h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }
    .card p {
      color: #94a3b8;
      font-size: 14px;
    }
    footer {
      text-align: center;
      color: #94a3b8;
      padding: 20px;
      font-size: 13px;
    }
  </style>
</head>
<body>

<header>
  <h1>📚 HSC পাঠ্যপুস্তক সমগ্র</h1>
  <p>একাদশ-দ্বাদশ শ্রেণির শিক্ষার্থীদের জন্য অনলাইন লাইব্রেরি</p>
</header>

<div class="container">
  <!-- বাংলা বইয়ের কার্ড -->
  <a href="bangla.html" class="card">
    <h3>📖 বাংলা</h3>
    <p>প্রথম ও দ্বিতীয় পত্র</p>
  </a>

  <!-- ইংরেজি বইয়ের কার্ড (ভবিষ্যতে বাড়ানোর জন্য) -->
  <a href="#" class="card">
    <h3>🇬🇧 ইংরেজি</h3>
    <p>প্রথম ও দ্বিতীয় পত্র</p>
  </a>

  <!-- আইসিটি বইয়ের কার্ড -->
  <a href="#" class="card">
    <h3>💻 ICT</h3>
    <p>তথ্য ও যোগাযোগ প্রযুক্তি</p>
  </a>
</div>

<footer>
  © 2026 HSC পাঠ্যপুস্তক সমগ্র
</footer>

</body>
</html>
