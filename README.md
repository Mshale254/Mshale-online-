
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MSHALE-IT-TECH • Online Cyber Services</title>
  <meta name="description" content="All online cyber services in one place: eCitizen, KRA, HELB, NSSF, SHIF, TSC, NTSA, police clearance, business registration, printing & more. Call/WhatsApp 0729829406." />
  <meta name="theme-color" content="#0aa558" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 128 128'%3E%3Crect width='128' height='128' rx='24' fill='%230aa558'/%3E%3Cpath d='M30 64h68M64 30v68' stroke='white' stroke-width='14' stroke-linecap='round'/%3E%3C/svg%3E"/>
  <style>
    :root{
      --bg: #071b12;
      --brand: #0aa558;
      --brand-2: #0f8f4a;
      --text: #e8ffee;
      --muted: #b6e6c7;
      --card: #0d2b1f;
      --border: #124a33;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;height:100%;scroll-behavior:smooth}
    body{
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, 'Helvetica Neue', Arial, 'Noto Sans', 'Apple Color Emoji','Segoe UI Emoji';
      background:
        radial-gradient(1200px 600px at 80% -10%, rgba(17,150,92,.35), transparent 60%),
        radial-gradient(1000px 500px at -10% 20%, rgba(5,70,45,.6), transparent 60%),
        var(--bg);
      color:var(--text);
      line-height:1.5;
    }
    a{color:inherit;text-decoration:none}
    .container{width:min(1100px, 92%);margin:0 auto}/* Header */
header{
  position:sticky;top:0;z-index:50;
  background:rgba(7,27,18,.75);backdrop-filter: blur(10px);
  border-bottom:1px solid rgba(255,255,255,.06);
}
nav{display:flex;align-items:center;justify-content:space-between;padding:.8rem 0}
.brand{display:flex;gap:.75rem;align-items:center;font-weight:800;letter-spacing:.2px}
.logo{width:36px;height:36px;border-radius:12px;background:linear-gradient(145deg,var(--brand),var(--brand-2));display:grid;place-items:center;box-shadow:var(--shadow)}
.logo svg{width:22px;height:22px}
.nav-actions{display:flex;gap:.6rem;flex-wrap:wrap}
.btn{padding:.7rem 1rem;border-radius:999px;border:1px solid var(--border);background:#0a2418;display:inline-flex;align-items:center;gap:.5rem;font-weight:600}
.btn.primary{background:linear-gradient(145deg,var(--brand),var(--brand-2));border:none}
.btn:hover{transform:translateY(-1px)}

/* Hero */
.hero{padding:clamp(3rem,5vw,5rem) 0 2rem}
.hero .wrap{display:grid;grid-template-columns:1.1fr .9fr;gap:2rem;align-items:center}
.hero h1{font-size:clamp(2rem,4.6vw,3.2rem);margin:.2rem 0 1rem;line-height:1.1}
.hero p{color:var(--muted);margin:0 0 1.2rem}
.hero .card{background:linear-gradient(180deg, rgba(17,150,92,.12), rgba(17,150,92,.05));border:1px solid var(--border);border-radius:var(--radius);padding:1rem 1.2rem}
.tag{display:inline-block;padding:.35rem .7rem;border-radius:999px;background:#0a2418;border:1px solid var(--border);color:var(--muted);font-weight:700;font-size:.8rem}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin-top:1rem}
.kpi{display:grid;grid-template-columns:repeat(3,1fr);gap:.8rem;margin-top:1rem}
.kpi .cell{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:.9rem;text-align:center}
.kpi .cell b{display:block;font-size:1.2rem}

/* Sections */
section{padding:2.2rem 0}
h2{font-size:clamp(1.4rem,2.6vw,2rem);margin:0 0 1rem}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem}
.card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:1rem;box-shadow:var(--shadow)}
.card h3{margin:.2rem 0 .6rem;font-size:1.05rem}
.card ul{margin:.4rem 0 0;padding-left:1.1rem}
.card li{margin:.3rem 0}

.cta{display:flex;flex-wrap:wrap;gap:.6rem;margin-top:1rem}

/* Contact */
.contact{display:grid;grid-template-columns:1.2fr .8fr;gap:1rem}
.contact .panel{padding:1rem;border-radius:var(--radius);border:1px solid var(--border);background:linear-gradient(180deg, rgba(10,165,88,.06), rgba(10,165,88,.02))}
.contact label{display:block;margin:.5rem 0 .2rem;color:var(--muted)}
.contact input, .contact textarea{
  width:100%;padding:.8rem;border-radius:12px;border:1px solid var(--border);background:#0a2418;color:var(--text)
}
.contact textarea{min-height:120px}

/* Footer */
footer{padding:2rem 0;border-top:1px solid rgba(255,255,255,.08);color:#c7f5da}
footer small{color:var(--muted)}

/* Responsive */
@media (max-width: 900px){
  .hero .wrap, .contact{grid-template-columns:1fr}
  .grid{grid-template-columns:1fr 1fr}
}
@media (max-width: 600px){
  .grid{grid-template-columns:1fr}
  .kpi{grid-template-columns:1fr 1fr}
  nav{gap:.6rem}
}


  <!-- Header -->
  <header>
    <div class="container">
      <nav>
        <div class="brand">
          <div class="logo" aria-hidden="true">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
              <path d="M4 12h16M12 4v16" stroke="#fff" stroke-width="2.2" stroke-linecap="round"/>
            </svg>
          </div>
          <div>
            <div style="font-size:1rem;opacity:.9">MSHALE-IT-TECH</div>
            <div style="font-size:.8rem;color:var(--muted)">Online Cyber Services • Kenya</div>
          </div>
        </div>
        <div class="nav-actions">
          <a class="btn" href="#services">Services</a>
          <a class="btn" href="#contact">Contact</a>
          <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">WhatsApp</a>
        </div>
      </nav>
    </div>
  </header>  <!-- Hero -->  <section class="hero">
    <div class="container wrap">
      <div>
        <span class="tag">Trusted Cyber Services • Fast & Reliable</span>
        <h1>All Your <span style="color:#9ef2bf">Online Cyber Services</span> in One Place</h1>
        <p>We handle government portals, education, finance, business, printing, passports & more — hassle‑free support on phone or WhatsApp. Professional IT assistance for individuals and businesses.</p>
        <div class="cta">
          <a class="btn primary" href="tel:+254729829406">Call 0729829406</a>
          <a class="btn" href="sms:+254729829406?body=Hello%20MSHALE-IT-TECH">Send SMS</a>
          <a class="btn" href="#services">Explore Services</a>
        </div>
        <div class="kpi">
          <div class="cell"><b>Same‑Day</b><small>Turnaround on most tasks</small></div>
          <div class="cell"><b>Secure</b><small>Data privacy guaranteed</small></div>
          <div class="cell"><b>Nationwide</b><small>Online assistance</small></div>
        </div>
      </div>
      <div>
        <div class="card">
          <h3 style="margin-top:0">Quick Request</h3>
          <p style="margin:.2rem 0 1rem;color:var(--muted)">Tell us what you need and we’ll assist you ASAP.</p>
          <form action="https://wa.me/254729829406" method="get" onsubmit="this.action='https://wa.me/254729829406?text='+encodeURIComponent('Name: '+this.name.value+'%0AService: '+this.service.value+'%0ADetails: '+this.details.value);">
            <label for="name">Your Name</label>
            <input id="name" name="name" placeholder="Enter your full name" required>
            <label for="service">Service Needed</label>
            <input id="service" name="service" placeholder="e.g. KRA PIN update, Police Clearance" required>
            <label for="details">Extra Details</label>
            <textarea id="details" name="details" placeholder="Add any helpful information..."></textarea>
            <div class="cta">
              <button class="btn primary" type="submit">Send via WhatsApp</button>
              <a class="btn" href="mailto:info@example.com?subject=Cyber%20Service%20Request">Or Email</a>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>  <!-- Services -->  <section id="services">
    <div class="container">
      <h2>Cyber Services</h2>
      <p style="color:var(--muted);margin-top:-.3rem">Comprehensive support across government portals, education, finance, business, IDs & documents, travel, and printing.</p><div class="grid" style="margin-top:1rem">
    <div class="card">
      <h3>Government (eCitizen)</h3>
      <ul>
        <li>Account creation & password recovery</li>
        <li>Birth, death & marriage certificates</li>
        <li>National ID replacement & updates</li>
        <li>Good Conduct (Police Clearance) applications</li>
        <li>NTSA: New DL, renewal, TIMS support</li>
        <li>Passport application & tracking</li>
        <li>Huduma services guidance</li>
      </ul>
    </div>

    <div class="card">
      <h3>Tax (KRA)</h3>
      <ul>
        <li>KRA PIN registration & update</li>
        <li>iTax setup & password reset</li>
        <li>Tax return filing (individual & business)</li>
        <li>Withholding & PAYE support</li>
        <li>Compliance certificates</li>
      </ul>
    </div>

    <div class="card">
      <h3>Education (HELB & KUCCPS)</h3>
      <ul>
        <li>HELB: application & portal update (100%)</li>
        <li>Inter‑institutional transfers</li>
        <li>Loan status checks & appeals guidance</li>
        <li>Fee structures & admission support</li>
      </ul>
    </div>

    <div class="card">
      <h3>Social Funds</h3>
      <ul>
        <li>SHIF (formerly NHIF) registration & updates</li>
        <li>NSSF registration & employer portal</li>
        <li>Social benefit claims guidance</li>
      </ul>
    </div>

    <div class="card">
      <h3>Jobs & Professional</h3>
      <ul>
        <li>TSC Number application assistance</li>
        <li>ECitizen job portal setup</li>
        <li>CV writing & professional profiles</li>
        <li>Police clearance for jobs & travel</li>
      </ul>
    </div>

    <div class="card">
      <h3>Business Services</h3>
      <ul>
        <li>Business name search & registration</li>
        <li>CR12, company registration guidance</li>
        <li>eTIMS onboarding support</li>
        <li>Business permits & licenses guidance</li>
      </ul>
    </div>

    <div class="card">
      <h3>Banking & Mobile Money</h3>
      <ul>
        <li>Paybill/Till creation guidance</li>
        <li>Account linking & reversals guidance</li>
        <li>Statement downloads (bank & M‑Pesa)</li>
      </ul>
    </div>

    <div class="card">
      <h3>Documents & Printing</h3>
      <ul>
        <li>Typing, editing & formatting</li>
        <li>Printing, scanning & photocopy</li>
        <li>Passport photos & photo retouch</li>
        <li>Binding, lamination & certificates</li>
        <li>PDF conversions & e‑signatures</li>
      </ul>
    </div>

    <div class="card">
      <h3>IT & Web Support</h3>
      <ul>
        <li>Website design (personal & business)</li>
        <li>Email setup & domain guidance</li>
        <li>Computer troubleshooting</li>
        <li>Safe cyber hygiene & backups</li>
        <li>Social media page setup & verification</li>
      </ul>
    </div>
  </div>

  <div class="cta" style="margin-top:1rem">
    <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">Order on WhatsApp</a>
    <a class="btn" href="tel:+254729829406">Call Now</a>
  </div>
</div>

  </section>  <!-- Contact -->  <section id="contact">
    <div class="container contact">
      <div class="panel">
        <h2>Contact & Support</h2>
        <p style="color:var(--muted);margin-top:-.4rem">Reach out for quick assistance. Online support available nationwide.</p>
        <div class="cta">
          <a class="btn primary" href="https://wa.me/254729829406" target="_blank" rel="noopener">WhatsApp: 0729829406</a>
          <a class="btn" href="tel:+254729829406">Call</a>
          <a class="btn" href="sms:+254729829406">SMS</a>
        </div>
        <div style="margin-top:1rem">
          <div><b>Working Hours:</b> Mon–Sat • 8:00am – 7:00pm</div>
          <div><b>Payments:</b> M‑Pesa, Bank, Cash</div>
        </div>
      </div>
      <div class="panel">
        <h3 style="margin-top:0">Direct Email</h3>
        <form action="mailto:info@example.com" method="post" enctype="text/plain">
          <label for="ename">Your Name</label>
          <input id="ename" name="name" placeholder="e.g. John Doe" required>
          <label for="eemail">Email</label>
          <input id="eemail" type="email" name="email" placeholder="you@example.com" required>
          <label for="emsg">Message</label>
          <textarea id="emsg" name="message" placeholder="How can we help?"></textarea>
          <div class="cta">
            <button class="btn primary" type="submit">Send Email</button>
          </div>
        </form>
      </div>
    </div>
  </section>  <footer>
    <div class="container">
      <div style="display:flex;justify-content:space-between;gap:1rem;flex-wrap:wrap;align-items:center">
        <div>
          <b>MSHALE-IT-TECH</b>
          <div style="color:var(--muted)">All Online Cyber Services • Kenya</div>
        </div>
        <div>
          <small>Tel/WhatsApp: <a href="tel:+254729829406">0729829406</a></small>
        </div>
      </div>
      <div style="margin-top:.8rem;color:var(--muted)">
        <small>© <span id="year"></span> Mshale IT Tech. All rights reserved.</small>
      </div>
    </div>
  </footer>  <script>
    // Set current year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html>    .price{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;font-weight:700}

    /* Cybersecurity Tools Section */
    .cybertools{
      margin-top:30px;
      background:green;
      border-radius:14px;
      padding:60px 20px;
      text-align:center;
      display:flex;
      justify-content:center;
      align-items:center;
    }
    .cybertools a{
      color:white;
      font-size:28px;
      font-family:Arial, sans-serif;
      text-decoration:none;
      font-weight:bold;
      background:rgba(0,0,0,0.3);
      padding:15px 25px;
      border-radius:12px;
      transition:0.3s;
    }
    .cybertools a:hover{background:rgba(255,255,255,0.2)}

    footer{margin-top:26px;padding:16px;border-radius:10px;background:linear-gradient(180deg,transparent, rgba(255,255,255,0.01));display:flex;justify-content:space-between;align-items:center;font-size:14px}
    a.whitelink{color:var(--muted);text-decoration:none}
    a.whitelink:hover{color:#fff}

    @media (max-width:880px){
      .hero{grid-template-columns:1fr;}
      .services{grid-template-columns:1fr}
      footer{flex-direction:column;gap:8px;text-align:center}
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
    </header>

    <section class="hero">
      <div class="hero-left">
        <h2>Inbox for the following cyber services</h2>
        <p>We handle official applications and account support. <br>NOTE: illegal or fraudulent document editing is not offered.</p>

        <div class="cta">
          <a class="btn" href="https://wa.me/254729829406" target="_blank">Message on WhatsApp</a>
          <a class="btn ghost" href="#services">View Services</a>
        </div>

        <div class="vpn">
          <strong>AIRTEL UNLIMITED VPN FILES AVAILABLE</strong>
          <div style="margin-top:8px">Supported: Http injector • Http custom • Dark tunnel • Ev2ray</div>
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

    <!-- New Cybersecurity Tools Section -->
    <section class="cybertools">
      <a href="https://mshale254.github.io/Mshale-online-cyber-services/#services">
        Free Cybersecurity & Defensive Tools
      </a>
    </section>

    <footer>
      <div>POWERED BY <strong>MSHALE-TECH</strong> — Stay Connected</div>
      <div><a class="whitelink" href="https://chat.whatsapp.com/KNbTxPDw0Et1rxWYcXPg3p" target="_blank">Join our WhatsApp group</a></div>
    </footer>
  </div>
</body>

