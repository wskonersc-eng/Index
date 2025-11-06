<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>เว็บไซต์ของฉัน</title>
  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Kanit', sans-serif; line-height: 1.6; background-color: #f9f9f9; color: #333; }

    header {
      background: linear-gradient(to right, #3498db, #2ecc71);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 { font-size: 2.8rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; }

    nav {
      background-color: #2980b9;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    nav a:hover { background-color: #1abc9c; }

    section {
      padding: 60px 20px;
      text-align: center;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #3498db;
    }
    section p { max-width: 700px; margin: 0 auto 20px auto; }

    /* Portfolio images */
    .portfolio {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 30px;
    }
    .portfolio img {
      width: 250px;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .portfolio img:hover { transform: scale(1.05); }

    .button {
      display: inline-block;
      background-color: #e74c3c;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .button:hover { background-color: #c0392b; }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    /* Responsive */
    @media (max-width: 768px) {
      header h1 { font-size: 2rem; }
      section { padding: 40px 15px; }
      nav a { padding: 10px 15px; }
      .portfolio img { width: 90%; height: auto; }
    }
  </style>
</head>
<body>

<header>
  <h1>ยินดีต้อนรับสู่เว็บไซต์ของฉัน</h1>
  <p>เว็บไซต์ตัวอย่างที่สวยงาม พร้อมรูปภาพและไอคอน</p>
</header>

<nav>
  <a href="#about">เกี่ยวกับฉัน</a>
  <a href="#services">บริการ</a>
  <a href="#portfolio">ผลงาน</a>
  <a href="#contact">ติดต่อ</a>
</nav>

<section id="about">
  <h2>เกี่ยวกับฉัน</h2>
  <p>สวัสดีครับ! ผมสร้างเว็บไซต์นี้เพื่อแสดงผลงานและบริการด้านเทคโนโลยีต่าง ๆ โดยเน้นความเรียบง่าย สวยงาม และรองรับมือถือ</p>
</section>

<section id="services">
  <h2>บริการของฉัน</h2>
  <p>ผมให้บริการออกแบบเว็บไซต์ พัฒนาเว็บแอปพลิเคชัน และให้คำปรึกษาด้านเทคโนโลยี เพื่อช่วยธุรกิจของคุณเติบโตบนโลกออนไลน์</p>
  <a href="#contact" class="button">ติดต่อฉัน</a>
</section>

<section id="portfolio">
  <h2>ผลงาน</h2>
  <p>นี่คือตัวอย่างผลงานที่ผมเคยสร้างให้ลูกค้าและโครงการส่วนตัว</p>
  <div class="portfolio">
    <img src="https://source.unsplash.com/250x150/?website,1" alt="Portfolio 1">
    <img src="https://source.unsplash.com/250x150/?website,2" alt="Portfolio 2">
    <img src="https://source.unsplash.com/250x150/?website,3" alt="Portfolio 3">
  </div>
</section>

<section id="contact">
  <h2>ติดต่อ</h2>
  <p>อีเมล: example@email.com</p>
  <p>โทร: 012-345-6789</p>
  <p>หรือติดต่อผ่านโซเชียลมีเดียของผม</p>
</section>

<footer>
  &copy; 2025 เว็บไซต์ของฉัน | สร้างด้วย HTML & CSS
</footer>

</body>
</html>
