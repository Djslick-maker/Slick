<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SlickPay Bank — Join the Red Drill Revolution</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>SlickPay Bank</header>
  <main>
    <h1>Join the Red Drill Revolution</h1>
    <h2>FDIC-Insured + Crypto-Ready Mobile Banking</h2>
    <p>Your money. Your rules. Instant accounts, crypto wallets, casino reloads, and biometric security — all in one slick app.</p>
    <ul class="features">
      <li>Instant account setup with easy KYC</li>
      <li>Virtual & physical debit cards</li>
      <li>Bitcoin & USDT wallet integration</li>
      <li>Casino reload and referral bonuses</li>
      <li>Biometric login & 2FA security</li>
    </ul>
    <!-- APK download button -->
    <a href="https://slickplay.global/downloads/SlickPlay_v1.0.apk" class="cta-button">Download Android App</a>
  </main>
  <footer>© 2025 SlickPay Bank. All rights reserved.</footer>
</body>
</html>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Open Sans', sans-serif;
  background: #0d0d0d;
  color: #f44336;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

header {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 2.5rem;
  text-align: center;
  padding: 40px 20px;
  letter-spacing: 0.1em;
  border-bottom: 2px solid #f44336aa;
}

main {
  flex: 1;
  max-width: 960px;
  margin: 40px auto;
  padding: 0 20px;
  text-align: center;
}

h1 {
  font-size: 3rem;
  margin-bottom: 0.3em;
  letter-spacing: 0.05em;
}

h2 {
  font-size: 1.6rem;
  font-weight: 700;
  color: #b71c1c;
  margin-bottom: 1.5em;
}

p {
  font-size: 1.1rem;
  color: #ddd;
  line-height: 1.5;
  margin-bottom: 2em;
}

.features {
  list-style: none;
  max-width: 600px;
  margin: 0 auto 2.5em;
  padding: 0;
  text-align: left;
}

.features li {
  position: relative;
  padding-left: 25px;
  margin-bottom: 1.1em;
  font-size: 1.1rem;
  font-weight: 600;
  color: #f44336;
}

.features li::before {
  content: '🔴';
  position: absolute;
  left: 0;
  top: 0;
  font-size: 1.2rem;
}

.cta-button {
  display: inline-block;
  padding: 15px 40px;
  font-size: 1.2rem;
  font-weight: 700;
  color: #fff;
  background-color: #f44336;
  border-radius: 50px;
  text-decoration: none;
  box-shadow: 0 4px 15px #f44336cc;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #b71c1c;
}

footer {
  text-align: center;
  padding: 15px 10px;
  font-size: 0.9rem;
  color: #777;
  border-top: 1px solid #333;
}

@media (max-width: 600px) {
  h1 { font-size: 2rem; }
  h2 { font-size: 1.3rem; }
  .features li { font-size: 1rem; }
  .cta-button {
    padding: 12px 30px;
    font-size: 1rem;
  }
}git clone https://github.com/yourusername/slickpay-bank.git
cd slickpay-bank
# create and paste the three files in this folder
git add index.html styles.css README.md
git commit -m "Initial landing page"
git push origin main Slick