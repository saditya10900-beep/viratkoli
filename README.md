
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Virat Kohli | Cricket Legend</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #07111e;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 7%;
      background: #101c2b;
    }

    .logo {
      color: #ffcc33;
      font-size: 22px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
    }

    nav a:hover {
      color: #ffcc33;
    }

    .hero {
      text-align: center;
      padding: 90px 20px;
      background: linear-gradient(135deg, #102e50, #07111e);
    }

    .hero h1 {
      font-size: clamp(38px, 7vw, 72px);
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #ffcc33;
    }

    .hero p {
      color: #d2d9e3;
      line-height: 1.8;
      margin-bottom: 25px;
    }

    button {
      background: #ffcc33;
      color: #111;
      border: none;
      padding: 14px 24px;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }

    section {
      padding: 55px 7%;
    }

    h2 {
      text-align: center;
      margin-bottom: 25px;
      color: #ffcc33;
    }

    .about {
      max-width: 800px;
      margin: auto;
      text-align: center;
      line-height: 1.9;
      color: #d2d9e3;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
      gap: 20px;
    }

    .card {
      background: #132238;
      padding: 28px 18px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid #283b53;
    }

    .card h3 {
      color: #ffcc33;
      margin-bottom: 12px;
    }

    .card p {
      color: #d2d9e3;
      line-height: 1.6;
    }

    .quote {
      text-align: center;
      font-size: 21px;
      line-height: 1.7;
      font-style: italic;
      max-width: 700px;
      margin: auto;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #101c2b;
      color: #bfc8d5;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        gap: 18px;
      }

      nav a {
        margin: 0 7px;
        font-size: 13px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">VK | CRICKET</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#career">Career</a>
      <a href="#records">Highlights</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <p>THE KING OF MODERN CRICKET</p>

    <h1>VIRAT <span>KOHLI</span></h1>

    <p>
      Passion. Discipline. Determination.<br>
      Celebrating one of cricket's most iconic players.
    </p>

    <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})">
      EXPLORE HIS JOURNEY
    </button>
  </section>

  <section id="about">
    <h2>About Virat Kohli</h2>

    <div class="about">
      Virat Kohli is an Indian international cricketer
      known for his batting, fitness and competitive spirit.
      He captained India in international cricket and has
      achieved remarkable success across formats.

      <p style="margin-top:15px">
        This fan website is created by Aditya Singh.
      </p>
    </div>
  </section>

  <section id="career">
    <h2>Career Highlights</h2>

    <div class="cards">
      <div class="card">
        <h3>ODI Cricket</h3>
        <p>Known for consistency and outstanding run chases.</p>
      </div>

      <div class="card">
        <h3>Test Cricket</h3>
        <p>Recognised for aggressive leadership and batting.</p>
      </div>

      <div class="card">
        <h3>T20 Cricket</h3>
        <p>Celebrated for match-winning performances.</p>
      </div>
    </div>
  </section>

  <section id="records">
    <h2>What Makes Him Special?</h2>

    <div class="cards">
      <div class="card">
        <h3>Batting</h3>
        <p>Exceptional technique and run-scoring ability.</p>
      </div>

      <div class="card">
        <h3>Fitness</h3>
        <p>A strong example of dedication to fitness.</p>
      </div>

      <div class="card">
        <h3>Leadership</h3>
        <p>Known for energy, intensity and commitment.</p>
      </div>
    </div>
  </section>

  <section>
    <div class="quote">
      "Dream big, work hard, stay focused."
      <p style="margin-top:15px;color:#ffcc33">
        — A fan-made inspirational message
      </p>
    </div>
  </section>

  <footer>
    <p>© 2026 Aditya Singh | Virat Kohli Fan Website</p>
    <p style="margin-top:8px">
      Unofficial fan project. Not affiliated with Virat Kohli.
    </p>
  </footer>

</body>
</html>
