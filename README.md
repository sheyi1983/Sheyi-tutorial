<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LearnHub Pro | Tutorials by Sheri Ajayi</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f4f4f4;
    }
    header {
      background: #111;
      color: #fff;
      padding: 1rem 0;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      overflow: hidden;
    }
    nav ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: #0b5ed7;
      color: white;
      text-align: center;
      padding: 4rem 1rem;
    }
    .hero h2 {
      font-size: 2.5rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin: 1rem 0;
    }
    .btn {
      background: #ffc107;
      color: #000;
      padding: 0.7rem 1.5rem;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #e0a800;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      padding: 2rem 1rem;
      background: #fff;
    }
    .feature {
      flex: 1 1 30%;
      background: #e9ecef;
      margin: 10px;
      padding: 1.5rem;
      border-radius: 8px;
      text-align: center;
    }
    footer {
      background: #111;
      color: #ccc;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        align-items: center;
      }
      .features {
        flex-direction: column;
        align-items: center;
      }
      .feature {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1 style="text-align:center;">LearnHub Pro</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Courses</a></li>
          <li><a href="#">Schedule</a></li>
          <li><a href="#">Enroll</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>Master Your Subjects with Sheri Ajayi</h2>
      <p>JSS1 to SS3 | JAMB | Online and Physical Tutorials Available</p>
      <a href="#" class="btn">Enroll Now</a>
    </div>
  </section>

  <section class="features container">
    <div class="feature">
      <h3>📚 Online Classes</h3>
      <p>Join live Zoom or recorded classes from anywhere in Nigeria.</p>
    </div>
    <div class="feature">
      <h3>🏫 Physical Tutorials</h3>
      <p>Available in Tunga-Maje, Gwagwalada — experience one-on-one tutoring.</p>
    </div>
    <div class="feature">
      <h3>💳 Secure Payments</h3>
      <p>Pay easily using Paystack or Flutterwave and receive automatic confirmation.</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 LearnHub Pro. Designed by Sheri Ajayi | 08078163775</p>
    </div>
  </footer>

</body>
</html> Sheyi-tutorial
