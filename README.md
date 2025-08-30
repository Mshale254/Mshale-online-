<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MSHALE-IT-TECH — Online Cyber Services</title>
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --accent1: #6EE7B7; /* mint */
      --accent2: #60A5FA; /* sky */
      --accent3: #F472B6; /* pink */
      --muted: #9AA6B2;
      --glass: rgba(255,255,255,0.04);
      --radius: 14px;
      --max-width: 1100px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }*{box-sizing:border-box}
html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#071022);color:#e6eef6}
.container{max-width:var(--max-width);margin:36px auto;padding:28px}

header{display:flex;gap:16px;align-items:center;justify-content:space-between}
.brand{display:flex;gap:12px;align-items:center}
.logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent2),var(--accent1));display:flex;align-items:center;justify-content:center;font-weight:700;color:#04263b}
h1{font-size:20px;margin:0}
p.lead{margin:4px 0 0;color:var(--muted);font-size:13px}

.hero{margin-top:22px;background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:20px;border-radius:var(--radius);display:grid;grid-template-columns:1fr 320px;gap:20px;align-items:center}
.hero-left h2{margin:0 0 8px;font-size:22px}
.hero-left p{margin:0;color:var(--muted)}
.cta{margin-top:12px;display:flex;gap:10px}
.btn{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#012029;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--accent1)}

.contact-card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:16px;border-radius:12px;text-align:center}
.contact-card a{display:inline-block;margin-top:10px;padding:10px 12px;border-radius:10px;text-decoration:none;background:linear-gradient(90deg,var(--accent3),var(--accent2));color:#071022;font-weight:700}

.services{margin-top:22px;display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.card{background:var(--card);padding:16px;border-radius:12px;border:1px solid var(--glass)}
.card h3{margin:0 0 8px}
.list{display:grid;gap:8px}
.list .item{display:flex;align-items:center;gap:10px;padding:8px;border-radius:8px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent)}
.pulse{width:10px;height:10px;border-radius:50%;background:linear-gradient(180deg,var(--accent1),var(--accent2));box-shadow:0 0 8px rgba(96,165,250,0.18)}

.vpn{margin-top:12px;padding:12px;border-radius:10px;background:linear-gradient(90deg, rgba(96,165,250,0.06), rgba(244,114,182,0.03));border:1px solid rgba(255,255,255,0.03)}
.pricing{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.price{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;font-weight:700}

footer{margin-top:26px;padding:16px;border-radius:10px;background:linear-gradient(180deg,transparent, rgba(255,255,255,0.01));display:flex;justify-content:space-between;align-items:center}
a.whitelink{color:var(--muted);text-decoration:none}

@media (max-width:880px){
  .hero{grid-template-columns:1fr;}
  .services{grid-template-columns:1fr}
}

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">MS</div>
        <div>
          <h1>MSHALE-IT-TECH</h1>
          <p class="lead">MSHALE Online Cyber Services — fast, secure, reliable</p>
        </div>
      </div>
      <div style="text-align:right">
        <div style="font-weight:700">Contact</div>
        <a class="whitelink" href="https://wa.me/254729829406" target="_blank">+254 729 829 406 (WhatsApp)</a>
      </div>
    </header><section class="hero">
  <div class="hero-left">
    <h2>Inbox for the following cyber services</h2>
    <p>We handle official applications and account support. NOTE: illegal or fraudulent document editing is not offered.</p>

    <div class="cta">
      <a class="btn" href="https://wa.me/254729829406" target="_blank">Message on WhatsApp</a>
      <a class="btn ghost" href="#services">View Services</a>
    </div>

    <div class="vpn">
      <strong>`AIRTEL UNLIMITED VPN FILES AVAILABLE`</strong>
      <div style="margin-top:8px">Supported files: Http injector • Http custom • Dark tunnel • Ev2ray</div>
      <div class="pricing">
        <div class="price">4 days — 50 KSH</div>
        <div class="price">1 week — 80 KSH</div>
        <div class="price">10 days — 100 KSH</div>
        <div class="price">15 days — 150 KSH</div>
        <div class="price">30 days — 300 KSH</div>
      </div>
    </div>
  </div>

  <aside class="contact-card">
    <div style="font-weight:700">Quick Contact</div>
    <div style="font-size:12px;color:var(--muted);margin-top:6px">First come, first served</div>
    <a href="https://wa.me/254729829406" target="_blank">Open WhatsApp Chat</a>
  </aside>
</section>

<section id="services" class="services">
  <div class="card">
    <h3>Education & Student</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Changing HELB payment method (M-Pesa ↔ Bank)</div>
      <div class="item"><div class="pulse"></div>Updating HELB portal profile (up to 100%)</div>
      <div class="item"><div class="pulse"></div>Inter-institutional transfer</div>
      <div class="item"><div class="pulse"></div>HELB application assistance</div>
    </div>
  </div>

  <div class="card">
    <h3>Government & IDs</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>KRA PIN registration</div>
      <div class="item"><div class="pulse"></div>SHA / SHIF registration</div>
      <div class="item"><div class="pulse"></div>NSSF registration</div>
      <div class="item"><div class="pulse"></div>Good conduct application support</div>
      <div class="item"><div class="pulse"></div>Passport application guidance</div>
      <div class="item"><div class="pulse"></div>Birth & Marriage certificate applications</div>
    </div>
  </div>

  <div class="card">
    <h3>Professional & Exams</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Renewal / New Driving Licence application</div>
      <div class="item"><div class="pulse"></div>TSC NO application help</div>
      <div class="item"><div class="pulse"></div>ETIMS account creation</div>
      <div class="item"><div class="pulse"></div>CRB Clearance certificate assistance</div>
    </div>
  </div>

  <div class="card">
    <h3>Digital & Social</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Social media boosting panel / software</div>
      <div class="item"><div class="pulse"></div>Social media account management</div>
      <div class="item"><div class="pulse"></div>Premium apps available — no subscription</div>
    </div>
  </div>
</section>

<footer>
  <div>POWERED BY <strong>MSHALE-TECH</strong> — Stay Connected</div>
  <div><a class="whitelink" href="https://chat.whatsapp.com/KNbTxPDw0Et1rxWYcXPg3p" target="_blank">Join our WhatsApp group</a></div>
</footer>

  </div>
</body>
</html>.price{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;font-weight:700}

footer{margin-top:26px;padding:16px;border-radius:10px;background:linear-gradient(180deg,transparent, rgba(255,255,255,0.01));display:flex;justify-content:space-between;align-items:center}
a.whitelink{color:var(--muted);text-decoration:none}

@media (max-width:880px){
  .hero{grid-template-columns:1fr;}
  .services{grid-template-columns:1fr}
}

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">MS</div>
        <div>
          <h1>MSHALE-IT-TECH</h1>
          <p class="lead">MSHALE Online Cyber Services — fast, secure, reliable</p>
        </div>
      </div>
      <div style="text-align:right">
        <div style="font-weight:700">Contact</div>
        <a class="whitelink" href="https://wa.me/254729829406" target="_blank">+254 729 829 406 (WhatsApp)</a>
      </div>
    </header><section class="hero">
  <div class="hero-left">
    <h2>Inbox for the following cyber services</h2>
    <p>We handle official applications and account support. NOTE: illegal or fraudulent document editing is not offered.</p>

    <div class="cta">
      <a class="btn" href="https://wa.me/254729829406" target="_blank">Message on WhatsApp</a>
      <a class="btn ghost" href="#services">View Services</a>
    </div>

    <div class="vpn">
      <strong>`AIRTEL UNLIMITED VPN FILES AVAILABLE`</strong>
      <div style="margin-top:8px">Supported files: Http injector • Http custom • Dark tunnel • Ev2ray</div>
      <div class="pricing">
        <div class="price">4 days — 50 KSH</div>
        <div class="price">1 week — 80 KSH</div>
        <div class="price">10 days — 100 KSH</div>
        <div class="price">15 days — 150 KSH</div>
        <div class="price">30 days — 300 KSH</div>
      </div>
    </div>
  </div>

  <aside class="contact-card">
    <div style="font-weight:700">Quick Contact</div>
    <div style="font-size:12px;color:var(--muted);margin-top:6px">First come, first served</div>
    <a href="https://wa.me/254729829406" target="_blank">Open WhatsApp Chat</a>
  </aside>
</section>

<section id="services" class="services">
  <div class="card">
    <h3>Education & Student</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Changing HELB payment method (M-Pesa ↔ Bank)</div>
      <div class="item"><div class="pulse"></div>Updating HELB portal profile (up to 100%)</div>
      <div class="item"><div class="pulse"></div>Inter-institutional transfer</div>
      <div class="item"><div class="pulse"></div>HELB application assistance</div>
    </div>
  </div>

  <div class="card">
    <h3>Government & IDs</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>KRA PIN registration</div>
      <div class="item"><div class="pulse"></div>SHA / SHIF registration</div>
      <div class="item"><div class="pulse"></div>NSSF registration</div>
      <div class="item"><div class="pulse"></div>Good conduct application support</div>
      <div class="item"><div class="pulse"></div>Passport application guidance</div>
      <div class="item"><div class="pulse"></div>Birth & Marriage certificate applications</div>
    </div>
  </div>

  <div class="card">
    <h3>Professional & Exams</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Renewal / New Driving Licence application</div>
      <div class="item"><div class="pulse"></div>TSC NO application help</div>
      <div class="item"><div class="pulse"></div>ETIMS account creation</div>
      <div class="item"><div class="pulse"></div>CRB Clearance certificate assistance</div>
    </div>
  </div>

  <div class="card">
    <h3>Digital & Social</h3>
    <div class="list">
      <div class="item"><div class="pulse"></div>Social media boosting panel / software</div>
      <div class="item"><div class="pulse"></div>Social media account management</div>
      <div class="item"><div class="pulse"></div>Premium apps available — no subscription</div>
    </div>
  </div>
</section>

<footer>
  <div>POWERED BY <strong>MSHALE-TECH</strong> — Stay Connected</div>
  <div><a class="whitelink" href="https://chat.whatsapp.com/KNbTxPDw0Et1rxWYcXPg3p" target="_blank">Join our WhatsApp group</a></div>
</footer>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cybersecurity Tools</title>
  <style>
    body {
      background-color: green;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    a {
      color: white;
      font-size: 28px;
      font-family: Arial, sans-serif;
      text-decoration: none;
      font-weight: bold;
      background: rgba(0, 0, 0, 0.3);
      padding: 15px 25px;
      border-radius: 12px;
    }
    a:hover {
      background: rgba(255, 255, 255, 0.2);
    }
  </style>
</head>
<body>
  <a href="https://mshale254.github.io/Mshale-online-cyber-services/#services">
    Free Cybersecurity & Defensive Tools
  </a>
</body>
</html>
  </div>
</body>
