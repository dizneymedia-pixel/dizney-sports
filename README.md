
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dizney Sports</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #071A2B;
      color: #F5F7FA;
    }

    header {
      padding: 22px 16px;
      background: #0D2742;
      text-align: center;
      border-bottom: 2px solid #B7F000;
    }

    .brand {
      color: #B7F000;
      font-size: 30px;
      font-weight: 900;
      letter-spacing: 2px;
    }

    .subtitle {
      color: #20C9FF;
      margin-top: 5px;
      font-size: 13px;
      letter-spacing: 3px;
    }

    nav {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding: 12px;
      background: #071A2B;
    }

    nav button {
      white-space: nowrap;
      border: 1px solid #20C9FF;
      background: #0D2742;
      color: white;
      padding: 9px 14px;
      border-radius: 20px;
    }

    .container {
      padding: 15px;
      max-width: 900px;
      margin: auto;
    }

    .section-title {
      color: #B7F000;
      margin: 20px 0 10px;
      font-size: 18px;
    }

    .markets {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }

    .market {
      background: #0D2742;
      border-radius: 12px;
      padding: 15px;
      text-align: center;
      border: 1px solid #183C5C;
    }

    .market strong {
      display: block;
      color: #20E875;
      font-size: 20px;
    }

    .match {
      background: #0D2742;
      margin-top: 12px;
      padding: 16px;
      border-radius: 15px;
      border-left: 4px solid #B7F000;
    }

    .live {
      color: #FF3B4A;
      font-weight: bold;
      margin-bottom: 8px;
    }

    .teams {
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 12px;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 7px;
    }

    .stat {
      background: #071A2B;
      padding: 9px 4px;
      border-radius: 8px;
      text-align: center;
      font-size: 12px;
    }

    .stat b {
      display: block;
      color: #20C9FF;
      font-size: 15px;
      margin-top: 3px;
    }

    footer {
      text-align: center;
      padding: 30px 10px;
      color: #7890A5;
      font-size: 12px;
    }
  </style>
</head>

<body>

<header>
  <div class="brand">DIZNEY SPORTS</div>
  <div class="subtitle">SOCCER ANALYTICS</div>
</header>

<nav>
  <button>🔴 LIVE</button>
  <button>TODAY</button>
  <button>NEXT 7 DAYS</button>
  <button>SEARCH</button>
</nav>

<div class="container">

  <h2 class="section-title">⚽ GOAL MARKETS</h2>

  <div class="markets">
    <div class="market">Over 1.5<strong>92%</strong></div>
    <div class="market">Over 2.5<strong>76%</strong></div>
    <div class="market">Over 3.5<strong>48%</strong></div>
    <div class="market">Over 4.5<strong>27%</strong></div>
    <div class="market">Over 5.5<strong>11%</strong></div>
    <div class="market">HT Over 0.5<strong>81%</strong></div>
  </div>

  <h2 class="section-title">🔥 TODAY'S MATCHES</h2>

  <div class="match">
    <div class="live">🔴 LIVE 72'</div>
    <div class="teams">ARSENAL 2 — 1 CHELSEA</div>

    <div class="stats">
      <div class="stat">HT Goal<b>79%</b></div>
      <div class="stat">2–5 Goals<b>83%</b></div>
      <div class="stat">Home Win<b>55%</b></div>
      <div class="stat">Draw<b>25%</b></div>
      <div class="stat">Away Win<b>20%</b></div>
      <div class="stat">H2H<b>VIEW</b></div>
    </div>
  </div>

  <div class="match">
    <div class="live">⚽ UPCOMING</div>
    <div class="teams">BARCELONA — REAL MADRID</div>

    <div class="stats">
      <div class="stat">Over 1.5<b>88%</b></div>
      <div class="stat">Over 2.5<b>71%</b></div>
      <div class="stat">HT Goal<b>68%</b></div>
      <div class="stat">1X<b>82%</b></div>
      <div class="stat">X2<b>74%</b></div>
      <div class="stat">H2H<b>VIEW</b></div>
    </div>
  </div>

</div>

<footer>
  Dizney Sports © 2026<br>
  Personal soccer statistics dashboard
</footer>

</body>
</html>

After pasting: tap Preview to see it, then Commit changes to save it.
