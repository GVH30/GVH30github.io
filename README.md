<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Global Voyages & Hospitality — Courier Service</title>
  <style>
    :root{
      --bg:#000;
      --gold:#d4af37;
      --muted:#cfcfcf;
      --maxw:1100px;
      --radius:16px;
      --glass: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    body{margin:0; font-family:Inter, "Segoe UI", Roboto, Arial, sans-serif; background:var(--bg); color:var(--muted); -webkit-font-smoothing:antialiased}
    .container{max-width:var(--maxw); margin:30px auto; padding:24px}

    header{display:flex;align-items:center;gap:18px;padding:20px;border-radius:12px}
    .brand{display:flex;align-items:center;gap:16px}
    .logo{width:96px;height:96px;display:inline-block;border-radius:12px;overflow:hidden;background:linear-gradient(180deg,#0a0a0a,#111)}
    .logo img{width:100%;height:100%;object-fit:contain;display:block}
    .title{color:var(--gold)}
    .title h1{margin:0;font-size:26px;letter-spacing:1px}
    .title p{margin:2px 0 0;font-size:13px;color:var(--muted)}

    .hero{margin-top:18px;background:var(--glass);padding:28px;border-radius:14px;box-shadow:0 6px 20px rgba(0,0,0,0.6)}
    .hero-top{display:flex;align-items:center;justify-content:space-between;gap:20px}
    .hero-left{max-width:66%}
    .hero-left h2{color:var(--gold);margin:0 0 8px;font-size:28px}
    .hero-left p{margin:0;color:#cfcfcf}

    .banner{max-width:320px;border-radius:12px;overflow:hidden}
    .banner img{width:100%;display:block}

    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:20px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(212,175,55,0.07)}
    .card h3{margin:0 0 8px;color:var(--gold)}
    .card p{margin:0;color:var(--muted);font-size:14px}

    .contact-strip{margin-top:22px;background:linear-gradient(90deg, rgba(212,175,55,0.06), rgba(212,175,55,0.02));padding:16px;border-radius:12px;display:flex;align-items:center;justify-content:space-between;gap:12px}
    .phones{font-size:20px;color:white;font-weight:700}
    .address{font-size:14px;color:var(--muted)}

    .features{display:flex;gap:12px;flex-wrap:wrap;margin-top:18px}
    .pill{background:rgba(212,175,55,0.08);border:1px solid rgba(212,175,55,0.12);color:var(--gold);padding:8px 12px;border-radius:999px;font-weight:600;font-size:13px}

    footer{margin-top:30px;padding:20px;border-radius:12px;text-align:center;color:var(--muted);font-size:13px}

    /* responsive tweaks */
    @media(max-width:720px){
      .hero-top{flex-direction:column;align-items:flex-start}
      .hero-left{max-width:100%}
      .logo{width:76px;height:76px}
      .phones{font-size:18px}
    }

    /* small util */
    .muted{color:var(--muted)}
    a.cta{background:var(--gold);color:#051018;padding:10px 14px;border-radius:10px;font-weight:700;text-decoration:none}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">
          <!-- Replace 'logo.png' with your actual logo filename (uploaded image) -->
          <img src="logo.png" alt="GVH Logo" />
        </div>
        <div class="title">
          <h1>Global Voyages &amp; Hospitality</h1>
          <p>Courier Service — Domestic &amp; International</p>
        </div>
      </div>
      <div style="margin-left:auto;text-align:right">
        <div style="color:var(--gold);font-weight:700">Call / WhatsApp</div>
        <div style="font-size:18px;color:white;font-weight:700">9547508342 &nbsp;/&nbsp; 7001443800</div>
      </div>
    </header>

    <section class="hero">
      <div class="hero-top">
        <div class="hero-left">
          <h2>Fast — Safe — Trusted Courier Service</h2>
          <p>We specialise in secure parcel pickup and delivery across Diamond Harbour, South 24 Parganas and across India. Professional packaging, reliable tracking and friendly support.</p>

          <div class="features" style="margin-top:14px">
            <div class="pill">Pickup &amp; Drop</div>
            <div class="pill">Door-to-Door</div>
            <div class="pill">Intercity Delivery</div>
            <div class="pill">Packaging &amp; Handling</div>
          </div>

          <div style="margin-top:16px">
            <a class="cta" href="#contact">Book a Pickup</a>
            <a style="margin-left:12px;color:var(--muted);text-decoration:none;font-weight:600" href="#services">Our Services</a>
          </div>
        </div>

        <div class="banner">
          <!-- Replace 'Banner.jpg' with the banner image you provided -->
          <img src="Banner.jpg" alt="GVH Banner" />
        </div>
      </div>

      <div class="services" id="services">
        <div class="card">
          <h3>Domestic Courier</h3>
          <p>Fast and reliable domestic parcel delivery with network partners covering major cities.</p>
        </div>
        <div class="card">
          <h3>International Courier</h3>
          <p>International shipments handled with customs support and trusted international carriers.</p>
        </div>
        <div class="card">
          <h3>Pickup &amp; Packaging</h3>
          <p>Professional packaging and careful handling for safe transit of your goods.</p>
        </div>
        <div class="card">
          <h3>Business Accounts</h3>
          <p>Regular pickups and negotiated rates for small businesses and shops.</p>
        </div>
      </div>

      <div class="contact-strip" id="contact">
        <div>
          <div class="phones">9547508342 &nbsp;/&nbsp; 7001443800</div>
          <div class="address">Vill &amp; P.O. – Fatepur, P.S. – Falta, Dist. – South 24 Parganas, West Bengal, India — PIN: 743515</div>
        </div>
        <div style="text-align:right">
          <div style="font-size:13px;color:var(--muted)">Working Hours</div>
          <div style="font-weight:700;color:white">Mon – Sun: 9:00 AM — 9:00 PM</div>
        </div>
      </div>

    </section>

    <section style="margin-top:18px;background:var(--glass);padding:18px;border-radius:12px;">
      <h2 style="color:var(--gold);margin-top:0">About Our Courier Service</h2>
      <p class="muted">Global Voyages &amp; Hospitality Courier Service focuses exclusively on courier solutions — secure, timely and affordable. We do not accept fragile glass, perishables or prohibited items. For high-value shipments please contact us first to discuss insurance and packaging options.</p>
    </section>

    <section style="margin-top:18px;display:grid;grid-template-columns:1fr 360px;gap:18px;align-items:start">
      <div style="background:var(--glass);padding:18px;border-radius:12px;">
        <h3 style="color:var(--gold);margin-top:0">How to Book a Pickup</h3>
        <ol class="muted">
          <li>Call / WhatsApp us at <strong>9547508342</strong> or <strong>7001443800</strong>.</li>
          <li>Provide pickup address, package weight and destination.</li>
          <li>We confirm a pickup window and provide a tracking number.</li>
          <li>Payment can be made at pickup or via digital transfer.</li>
        </ol>
      </div>

      <aside style="background:var(--glass);padding:18px;border-radius:12px;">
        <h3 style="color:var(--gold);margin-top:0">Quick Details</h3>
        <p class="muted"><strong>Service Area:</strong> Diamond Harbour &amp; Intercity</p>
        <p class="muted"><strong>Restrictions:</strong> No perishables, no hazardous goods</p>
        <p class="muted"><strong>Email:</strong> globalcourierservices2030@gmail.com</p>
      </aside>
    </section>

    <footer>
      <div>© 2025 Global Voyages &amp; Hospitality — Courier Service</div>
      <div style="margin-top:8px;color:var(--muted);font-size:13px">Design note: replace <code>logo.png</code> and <code>Banner.jpg</code> files with your uploaded images in the same folder as this HTML file.</div>
    </footer>
  </div>
</body>
</html>
