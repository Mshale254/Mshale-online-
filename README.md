
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MSHALE • IT & Cyber Services</title>
  <meta name="description" content="Fast, reliable online cyber & IT services: HELB, KRA, NHIF/NSSF, TIMS, ETIMS, CRB, passport, printing, scanning, CV writing, social media, and more." />
  <meta name="theme-color" content="#0ea5e9" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0b1220;
      --card: #0f172a;
      --muted: #94a3b8;
      --text: #e2e8f0;
      --brand: #22c55e; /* green */
      --brand-2: #0ea5e9; /* sky */
      --ring: rgba(14,165,233,.3);
      --shadow: 0 10px 30px rgba(2,6,23,.35);
      --radius: 18px;
    }
    *{ box-sizing: border-box }
    html,body{ height:100% }
    body{
      margin:0; font-family: 'Outfit', system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
      background: radial-gradient(1200px 600px at 10% -10%, rgba(34,197,94,.20), transparent 60%),
                  radial-gradient(900px 500px at 110% 10%, rgba(14,165,233,.18), transparent 60%),
                  var(--bg);
      color:var(--text);
      line-height:1.6;
    }
    a{ color:inherit; text-decoration:none }
    .container{ width:min(1100px, 92%); margin-inline:auto }/* Header */
header{
  position:sticky; top:0; z-index:50; backdrop-filter: blur(14px);
  background:linear-gradient(180deg, rgba(2,6,23,.8), rgba(2,6,23,.45));
  border-bottom:1px solid rgba(148,163,184,.12);
}
.nav{
  display:flex; align-items:center; justify-content:space-between; padding:14px 0;
}
.brand{ display:flex; gap:10px; align-items:center; font-weight:700; letter-spacing:.2px }
.brand .logo{
  width:40px; height:40px; border-radius:12px; display:grid; place-items:center;
  background: conic-gradient(from 210deg, var(--brand), var(--brand-2));
  box-shadow: var(--shadow);
  color:#001b11; font-weight:800;
}
.tag{ font-size:.85rem; color:var(--muted) }
.cta{
  display:inline-flex; align-items:center; gap:10px; padding:10px 16px; border-radius:999px;
  background:linear-gradient(90deg, var(--brand), var(--brand-2));
  color:#001b11; font-weight:700; box-shadow: var(--shadow);
  border:0; cursor:pointer;
}

/* Hero */
.hero{ padding:64px 0 30px }
.hero-inner{ display:grid; grid-template-columns: 1.1fr .9fr; gap:30px; align-items:center }
@media (max-width: 900px){ .hero-inner{ grid-template-columns: 1fr } }
.hero h1{ font-size: clamp(1.9rem, 2.6vw + 1rem, 3rem); line-height:1.15; margin:10px 0 }
.hero p{ color:var(--muted); margin: 8px 0 20px }
.badges{ display:flex; flex-wrap:wrap; gap:10px; margin-top:14px }
.badge{
  padding:7px 12px; border-radius:999px; font-weight:600; font-size:.9rem;
  border:1px solid rgba(148,163,184,.22); background: rgba(15,23,42,.6)
}
.hero-card{
  background:linear-gradient(180deg, rgba(15,23,42,.9), rgba(15,23,42,.7));
  border:1px solid rgba(148,163,184,.14); padding:22px; border-radius: var(--radius);
  box-shadow: var(--shadow);
}
.hero-card h3{ margin:0 0 8px }
.list{ margin:0; padding-left:18px }
.list li{ margin:6px 0 }

/* Sections */
section{ padding:30px 0 }
.section-title{ display:flex; align-items:center; gap:10px; margin:8px 0 18px }
.section-title span{
  width:10px; height:10px; border-radius:3px; background:linear-gradient(90deg, var(--brand), var(--brand-2)); box-shadow:0 0 0 6px rgba(14,165,233,.16)
}

/* Cards grid */
.grid{ display:grid; grid-template-columns: repeat(3, 1fr); gap:16px }
@media (max-width: 1000px){ .grid{ grid-template-columns: repeat(2, 1fr) } }
@media (max-width: 640px){ .grid{ grid-template-columns: 1fr } }
.card{
  background:linear-gradient(180deg, rgba(15,23,42,.85), rgba(15,23,42,.55));
  border:1px solid rgba(148,163,184,.14); border-radius: var(--radius); padding:18px;
  transition: transform .25s ease, border-color .25s ease, box-shadow .25s ease;
}
.card:hover{ transform: translateY(-4px); border-color: rgba(14,165,233,.35); box-shadow: var(--shadow) }
.card h4{ margin:6px 0 4px }
.card p{ color:var(--muted); margin:0; font-size:.98rem }

/* Contact */
.contact{
  display:grid; grid-template-columns: .9fr 1.1fr; gap:20px; align-items:stretch
}
@media (max-width: 900px){ .contact{ grid-template-columns: 1fr } }
.panel{
  background:linear-gradient(180deg, rgba(15,23,42,.9), rgba(15,23,42,.6));
  border:1px solid rgba(148,163,184,.14); border-radius: var(--radius); padding:18px;
}
.row{ display:flex; gap:10px; align-items:center; margin:10px 0 }
.mono{ font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace }

/* Footer */
footer{ padding:30px 0 60px; color:var(--muted); text-align:center }

/* Floating WhatsApp */
.wa{ position: fixed; right:18px; bottom:18px; z-index:60 }
.wa a{
  display:flex; align-items:center; gap:10px; padding:12px 16px; border-radius:999px; font-weight:700;
  background:linear-gradient(90deg, #25D366, #128C7E);
  color:#001b11; box-shadow: var(--shadow); border:1px solid rgba(0,0,0,.08)
}
.visually-hidden{ position:absolute!important; height:1px; width:1px; overflow:hidden; clip:rect(1px,1px,1px,1px); white-space:nowrap }

  </style>
</head>
<body>
  <a class="visually-hidden" href="#main">Skip to content</a>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo">MS</div>
        <div>
          <div>MSHALE • IT & Cyber Services</div>
          <div class="tag">Fast • Reliable • 24/7</div>
        </div>
      </div>
      <a class="cta" href="https://wa.me/254729829406" target="_blank" rel="noopener">WhatsApp: 0729&nbsp;829406</a>
    </div>
  </header>  <main id="main" class="container">
    <section class="hero">
      <div class="hero-inner">
        <div>
          <h1>All Your Online & Cyber Services in One Place</h1>
          <p>We help with government portals, education services, tax, statements, printing, scanning, professional CVs, social media, and more — delivered quickly and correctly.</p>
          <div class="badges">
            <div class="badge">24/7 Support</div>
            <div class="badge">Fast Turnaround</div>
            <div class="badge">Secure & Confidential</div>
          </div>
          <div class="badges" style="margin-top:14px">
            <a class="cta" href="https://wa.me/254729829406" target="_blank" rel="noopener">Chat on WhatsApp</a>
            <a class="cta" style="background:linear-gradient(90deg, var(--brand-2), var(--brand))" href="#services">View Services</a>
          </div>
        </div>
        <div class="hero-card">
          <h3>Quick Help • Downloads & Printing</h3>
          <ul class="list">
            <li>Access & print pay slips, bank statements, and more</li>
            <li>Document editing (typos & info corrections) — legal only</li>
            <li>Printing, scanning, laminating & photocopying</li>
            <li>Typing & professional CV writing</li>
          </ul>
        </div>
      </div>
    </section><section id="services">
  <div class="section-title"><span></span><h2>Core Services</h2></div>
  <div class="grid">
    <article class="card">
      <h4>Data Entry Services</h4>
      <p>Entering or formatting large amounts of text or data as needed.</p>
    </article>
    <article class="card">
      <h4>Passport Application</h4>
      <p>Assistance completing and submitting your passport application online.</p>
    </article>
    <article class="card">
      <h4>ETIMS Account Creation</h4>
      <p>Set up your Electronic Tax Invoice Management System for business compliance.</p>
    </article>
    <article class="card">
      <h4>CRB Clearance Certificate</h4>
      <p>Apply for CRB report or clearance certificate (Credit Reference Bureau).</p>
    </article>
    <article class="card">
      <h4>Birth Certificate Application</h4>
      <p>Apply for or replace a birth certificate online.</p>
    </article>
    <article class="card">
      <h4>Social Media Boosting</h4>
      <p>Increase likes, followers, and views on TikTok, Facebook & Instagram.</p>
    </article>
    <article class="card">
      <h4>Social Media Management</h4>
      <p>Content posting, engagement & growth strategies for brands and individuals.</p>
    </article>
    <article class="card">
      <h4>Document Editing (Legal)</h4>
      <p>Correcting typos or info on digital documents (receipts, assignments, etc.).</p>
    </article>
    <article class="card">
      <h4>Printing & Scanning</h4>
      <p>Document printing, certificates, ID copies and high‑quality scanning.</p>
    </article>
    <article class="card">
      <h4>Laminating & Photocopying</h4>
      <p>Protect your documents and get clean photocopies fast.</p>
    </article>
    <article class="card">
      <h4>Typing & CV Writing</h4>
      <p>Professional CVs, application letters, and formatted documents.</p>
    </article>
    <article class="card">
      <h4>Email & Portal Access Help</h4>
      <p>Create or recover email accounts and access various online portals.</p>
    </article>
    <article class="card">
      <h4>Pay Slip & Statement Downloads</h4>
      <p>We help retrieve official pay slips, bank statements, and more.</p>
    </article>
  </div>
</section>

<section>
  <div class="section-title"><span></span><h2>Education, Tax & IDs (Kenya)</h2></div>
  <div class="grid">
    <article class="card"><h4>HELB Application</h4><p>Assisting students to apply for Higher Education Loans from the HELB portal.</p></article>
    <article class="card"><h4>Change HELB Payment Method</h4><p>Switch repayment mode (M-Pesa ⇄ Bank) and update details.</p></article>
    <article class="card"><h4>Update HELB Profile</h4><p>Complete or correct your HELB portal details to 100%.</p></article>
    <article class="card"><h4>Inter‑Institutional Transfer</h4><p>Apply for transfers between colleges/universities via KUCCPS.</p></article>
    <article class="card"><h4>KRA PIN Registration</h4><p>Register for an individual KRA PIN for tax purposes.</p></article>
    <article class="card"><h4>KRA Returns Filing</h4><p>Submit annual tax returns (employed & students) to avoid penalties.</p></article>
    <article class="card"><h4>NHIF Registration</h4><p>Register with Kenya's national health insurance fund.</p></article>
    <article class="card"><h4>NSSF Registration</h4><p>Sign up for Kenya’s social security savings fund.</p></article>
    <article class="card"><h4>Good Conduct Application</h4><p>Apply for a police clearance certificate.</p></article>
    <article class="card"><h4>DL Renewal / New DL</h4><p>Renew or apply for a driving license via TIMS.</p></article>
    <article class="card"><h4>TSC Number Application</h4><p>Help teachers apply for a TSC number for employment.</p></article>
  </div>
</section>

<section class="contact" id="contact">
  <div class="panel">
    <div class="section-title"><span></span><h2>Contact & Bookings</h2></div>
    <div class="row"><strong>WhatsApp:</strong> <a class="mono" href="https://wa.me/254729829406" target="_blank" rel="noopener">0729&nbsp;829406</a></div>
    <div class="row"><strong>Call:</strong> <a class="mono" href="tel:+254729829406">+254&nbsp;729&nbsp;829406</a></div>
    <p style="color:var(--muted); margin-top:12px">Messages are answered within minutes. Send a brief description of what you need and any reference numbers for faster service.</p>
    <div class="badges" style="margin-top:10px">
      <div class="badge">Secure Payments</div>
      <div class="badge">Privacy First</div>
      <div class="badge">Trusted by Students & SMEs</div>
    </div>
  </div>
  <form class="panel" onsubmit="event.preventDefault(); window.open('https://wa.me/254729829406?text='+encodeURIComponent(document.getElementById('msg').value),'_blank');">
    <div class="section-title"><span></span><h2>Quick Message</h2></div>
    <label for="msg" style="display:block; margin-bottom:8px">Tell us what you need help with:</label>
    <textarea id="msg" rows="6" style="width:100%; border-radius:12px; background:#0b1220; color:var(--text); border:1px solid rgba(148,163,184,.25); padding:12px"></textarea>
    <div style="display:flex; gap:10px; margin-top:12px">
      <button class="cta" type="submit">Send via WhatsApp</button>
      <a class="cta" style="background:linear-gradient(90deg, var(--brand-2), var(--brand))" href="#">Download Price List (coming soon)</a>
    </div>
  </form>
</section>

  </main>  <footer>
    <div class="container">
      <div>© <span id="y"></span> MSHALE • IT & Cyber Services. All rights reserved.</div>
      <div class="tag" style="margin-top:6px">This website does not process illegal requests. Document edits are limited to corrections that are lawful and verifiable.</div>
    </div>
  </footer>  <div class="wa">
    <a href="https://wa.me/254729829406" target="_blank" rel="noopener" aria-label="Chat on WhatsApp">
      <!-- WhatsApp icon -->
      <svg width="20" height="20" viewBox="0 0 32 32" fill="currentColor" aria-hidden="true"><path d="M19.11 17.06a5.74 5.74 0 0 1-2.44-.62 10.23 10.23 0 0 1-3.02-2.13 7.16 7.16 0 0 1-1.52-2.27c-.24-.56-.26-1.05.17-1.52.34-.38.8-.5 1.27-.33.19.07.38.16.56.26.22.12.35.32.47.54.15.26.29.53.46.77.21.29.17.57.02.87-.1.19-.19.38-.31.56-.19.29-.19.57.03.86.31.41.67.76 1.09 1.05.35.25.72.47 1.13.61.26.08.49.03.7-.15.24-.21.5-.39.75-.59.26-.2.52-.2.8-.06.42.22.84.45 1.24.71.29.18.48.44.47.8-.02.52-.18.99-.61 1.31-.35.25-.74.4-1.12.56-.2.1-.43.08-.66.08Z"/></svg>
      <span>WhatsApp</span>
    </a>
  </div>  <script>
    // Current year in footer
    document.getElementById('y').textContent = new Date().getFullYear();
  </script></body>
</html>
