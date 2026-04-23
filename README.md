# psychic-room-on-king
"Psychic Room on King — Personal readings, spiritual remedies, and curated tools in Charleston, SC"
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Psychic Room on King — Personal readings, spiritual remedies, and curated tools in Charleston, SC. Palmistry, intuitive readings, and compassionate guidance.">
  <meta name="theme-color" content="#1E1A20">
  <meta property="og:title" content="Psychic Room on King">
  <meta property="og:description" content="Find clarity that feels like coming home. Personal readings, spiritual remedies, and curated tools.">
  <meta property="og:image" content="https://images.unsplash.com/photo-1511974035430-5de47d3b95da?q=80&w=1200&auto=format&fit=crop">
  <title>Psychic Room on King | Charleston Readings & Spiritual Tools</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Root Variables */
    :root {
      --charcoal: #1E1A20;
      --gold: #C9A76B;
      --cream: #F6F3EE;
      --jade: #2E7A70;
      --mauve: #B79AA6;
      --glass: rgba(255,255,255,0.06);
      --radius: 12px;
      --max-width: 1100px;
      --transition: .22s ease;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color: var(--charcoal);
      background: linear-gradient(180deg, #F6F3EE 0%, #FBFAF8 100%);
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }

    /* Base Styles */
    * { box-sizing: border-box; }
    body { margin: 0; line-height: 1.5; min-height: 100vh; }
    a { transition: all var(--transition); }
    button { cursor: pointer; border: none; }

    /* Container */
    .container {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 28px;
    }

    /* Header */
    .header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 18px 0;
      border-bottom: 1px solid rgba(30, 26, 32, 0.04);
      margin-bottom: 14px;
    }
    .brand {
      display: flex;
      align-items: center;
      gap: 14px;
      text-decoration: none;
      color: var(--charcoal);
    }
    .logo-mark {
      width: 56px;
      height: 56px;
      border-radius: 14px;
      background: linear-gradient(135deg, var(--charcoal), #2b252b);
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--gold);
      font-weight: 700;
      font-family: "Playfair Display", Georgia, serif;
      font-size: 20px;
      box-shadow: 0 6px 20px rgba(30, 26, 32, 0.12);
    }
    .site-title {
      font-family: "Playfair Display", Georgia, serif;
      font-size: 18px;
      font-weight: 700;
      line-height: 1;
      margin: 0;
    }
    .site-sub {
      font-size: 12px;
      color: #6b666b;
      margin-top: 2px;
      margin: 0;
    }

    /* Navigation */
    .nav {
      display: flex;
      gap: 18px;
      align-items: center;
    }
    .nav a {
      color: var(--charcoal);
      text-decoration: none;
      padding: 8px 10px;
      border-radius: 8px;
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
    }
    .nav a:hover {
      background: rgba(30, 26, 32, 0.04);
    }

    /* CTA Button */
    .cta-book {
      background: linear-gradient(90deg, var(--gold), #d2b071);
      padding: 10px 16px;
      border-radius: 10px;
      color: var(--charcoal);
      text-decoration: none;
      font-weight: 700;
      font-size: 14px;
      box-shadow: 0 6px 18px rgba(201, 167, 107, 0.16);
      display: inline-block;
      border: none;
      cursor: pointer;
    }
    .cta-book:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 24px rgba(201, 167, 107, 0.24);
    }

    /* Mobile Menu */
    .mobile-menu {
      display: none;
      background: none;
      border: none;
      font-size: 24px;
      cursor: pointer;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(180deg, rgba(30, 26, 32, 0.04), rgba(30, 26, 32, 0.02));
      border-radius: 18px;
      padding: 36px;
      display: flex;
      gap: 36px;
      align-items: center;
      margin: 18px 0;
      box-shadow: 0 10px 40px rgba(30, 26, 32, 0.05);
    }
    .hero-left { flex: 1; min-width: 240px; }
    .hero-eyebrow {
      color: var(--jade);
      font-weight: 700;
      font-size: 13px;
      letter-spacing: 0.6px;
      text-transform: uppercase;
    }
    .hero-h {
      font-family: "Playfair Display", serif;
      font-size: 36px;
      margin: 8px 0;
      color: var(--charcoal);
      line-height: 1.2;
    }
    .hero-sub {
      color: #4b484b;
      font-size: 16px;
      margin-bottom: 18px;
      line-height: 1.6;
    }
    .hero-ctas {
      display: flex;
      gap: 12px;
      align-items: center;
      flex-wrap: wrap;
      margin-bottom: 16px;
    }
    .btn-outline {
      padding: 10px 14px;
      border-radius: 10px;
      border: 1px solid rgba(30, 26, 32, 0.08);
      background: transparent;
      color: var(--charcoal);
      text-decoration: none;
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
      display: inline-block;
      transition: all var(--transition);
    }
    .btn-outline:hover {
      background: rgba(30, 26, 32, 0.04);
      border-color: rgba(30, 26, 32, 0.12);
    }

    /* Trustbar */
    .trustbar {
      display: flex;
      gap: 12px;
      align-items: center;
      color: #5b575b;
      margin-top: 16px;
      font-size: 14px;
      flex-wrap: wrap;
    }
    .pulse {
      background: var(--gold);
      color: var(--charcoal);
      padding: 6px 8px;
      border-radius: 8px;
      font-weight: 700;
      box-shadow: 0 8px 22px rgba(201, 167, 107, 0.12);
      animation: pulse-animation 2s infinite;
    }
    @keyframes pulse-animation {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    /* Hero Image */
    .hero-right {
      width: 420px;
      height: 380px;
      border-radius: 14px;
      background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.15), rgba(0, 0, 0, 0.02));
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }
    .hero-photo {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      filter: grayscale(0.02) contrast(0.98) saturate(0.9);
    }

    /* Main Sections */
    .sections {
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: 28px;
      margin-top: 8px;
    }
    .main { background: transparent; }
    .side {
      position: sticky;
      top: 28px;
      align-self: start;
    }

    /* Cards */
    .card {
      background: #fff;
      border-radius: 14px;
      padding: 18px;
      box-shadow: 0 8px 30px rgba(18, 16, 18, 0.03);
      margin-bottom: 18px;
    }
    .card h2, .card h3, .card h4 {
      font-family: "Playfair Display", serif;
      margin: 0 0 8px;
    }
    .card h2 { font-size: 22px; }
    .card h4 { font-size: 16px; }

    /* Services Grid */
    .services {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 14px;
      margin: 8px 0;
    }
    .service {
      background: linear-gradient(180deg, #fff, #FBFBFB);
      padding: 18px;
      border-radius: 12px;
      border: 1px solid rgba(30, 26, 32, 0.04);
      transition: all var(--transition);
    }
    .service:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(30, 26, 32, 0.08);
    }
    .service h4 {
      margin: 0 0 8px;
      font-size: 16px;
      font-weight: 700;
    }
    .service p {
      margin: 0;
      color: #615d60;
      font-size: 14px;
    }

    /* Testimonials */
    .testimonials {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
      margin-top: 12px;
    }
    .testi {
      padding: 14px;
      border-radius: 12px;
      background: linear-gradient(180deg, #FFF9F3, #FFFDFB);
      border: 1px solid rgba(201, 167, 107, 0.06);
    }
    .testi p {
      margin: 0 0 8px;
      color: #3c3a3a;
      font-size: 14px;
      line-height: 1.5;
    }
    .testi .who {
      font-weight: 700;
      font-size: 13px;
      color: var(--charcoal);
      margin: 0;
    }

    /* Shop Grid */
    .shop-grid {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 12px;
    }
    .prod {
      flex: 1 1 140px;
      min-width: 120px;
      background: #fff;
      padding: 12px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid rgba(30, 26, 32, 0.04);
      transition: all var(--transition);
    }
    .prod:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(30, 26, 32, 0.08);
    }
    .prod img {
      width: 100%;
      height: 90px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 8px;
    }
    .prod h5 {
      margin: 4px 0;
      font-size: 14px;
      font-weight: 600;
    }
    .prod p {
      margin: 0;
      font-size: 12px;
      color: #6b666b;
    }

    /* About Section */
    .about-hero {
      display: flex;
      gap: 16px;
      align-items: center;
    }
    .about-hero img {
      width: 120px;
      height: 120px;
      border-radius: 12px;
      object-fit: cover;
      box-shadow: 0 10px 30px rgba(30, 26, 32, 0.06);
      flex-shrink: 0;
    }
    .about-hero div { flex: 1; }

    /* FAQ */
    .faq dl {
      margin: 0;
    }
    .faq dt {
      font-weight: 700;
      margin-top: 12px;
      color: var(--charcoal);
    }
    .faq dd {
      margin: 6px 0 0;
      color: #5b575b;
      padding-left: 0;
    }

    /* Contact Cards */
    .contact-row {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 12px;
    }
    .contact-card {
      flex: 1 1 200px;
      padding: 14px;
      border-radius: 12px;
      background: #fff;
      border: 1px solid rgba(30, 26, 32, 0.04);
    }
    .contact-card strong {
      display: block;
      color: var(--charcoal);
      margin-bottom: 4px;
    }
    .contact-card a {
      color: var(--jade);
      text-decoration: none;
    }
    .contact-card a:hover {
      text-decoration: underline;
    }

    /* Footer */
    .footer {
      margin-top: 28px;
      padding: 28px 0;
      color: #5b575b;
      font-size: 14px;
      border-top: 1px solid rgba(30, 26, 32, 0.04);
      text-align: center;
    }

    /* Sticky Book Button */
    .book-sticky {
      display: none;
      position: fixed;
      right: 18px;
      bottom: 18px;
      background: linear-gradient(90deg, var(--gold), #d2b071);
      color: var(--charcoal);
      padding: 12px 16px;
      border-radius: 14px;
      box-shadow: 0 14px 40px rgba(201, 167, 107, 0.18);
      z-index: 40;
      font-weight: 700;
      text-decoration: none;
      border: none;
    }
    .book-sticky:hover {
      transform: translateY(-2px);
      box-shadow: 0 18px 48px rgba(201, 167, 107, 0.24);
    }

    /* Responsive: Tablet */
    @media (max-width: 980px) {
      .hero {
        flex-direction: column;
        align-items: flex-start;
        padding: 22px;
      }
      .hero-right {
        width: 100%;
        height: 220px;
      }
      .sections {
        grid-template-columns: 1fr;
      }
      .side {
        position: static;
      }
      .site-title {
        font-size: 16px;
      }
      .nav {
        display: none;
      }
      .mobile-menu {
        display: block;
      }
      .brand {
        gap: 10px;
      }
      .hero-h {
        font-size: 28px;
      }
      .services {
        grid-template-columns: 1fr;
      }
      .testimonials {
        grid-template-columns: 1fr;
      }
      .book-sticky {
        display: block;
      }
      .about-hero {
        flex-direction: column;
        align-items: flex-start;
      }
      .about-hero img {
        width: 100%;
        height: auto;
        max-width: 200px;
      }
    }

    /* Responsive: Mobile */
    @media (max-width: 480px) {
      .container {
        padding: 16px;
      }
      .hero-h {
        font-size: 22px;
      }
      .logo-mark {
        width: 48px;
        height: 48px;
        font-size: 18px;
      }
      .hero-sub {
        font-size: 15px;
      }
      .hero-ctas {
        flex-direction: column;
        width: 100%;
      }
      .hero-ctas a {
        width: 100%;
        text-align: center;
      }
      .trustbar {
        flex-direction: column;
        align-items: flex-start;
      }
      .shop-grid {
        flex-direction: column;
      }
      .prod {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <header class="header">
      <a href="#" class="brand">
        <div class="logo-mark">P</div>
        <div>
          <div class="site-title">Psychic Room on King</div>
          <p class="site-sub">Charleston, SC</p>
        </div>
      </a>
      <nav class="nav">
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#shop">Shop</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="#booking"<!-- Hero Section -->
<section class="hero">
  <div class="hero-left">
    <div class="hero-eyebrow">✨ Clarity • Comfort • Courage</div>
    <h1 class="hero-h">Find clarity that feels like coming home</h1>
    <p class="hero-sub">Personal readings, spiritual remedies, and curated tools — honest, compassionate, and transformative. Walk-ins welcome; appointments recommended.</p>
    <div class="hero-ctas">
      <a href="#booking" class="cta-book">Book a Reading</a>
      <a href="#services" class="btn-outline">View Services</a>
    </div>
    <div class="trustbar">
      <div class="pulse">Locally loved</div>
      <div>Accurate readings • Candles & stones • Warm, private space</div>
    </div>
  </div>
  <div class="hero-right" aria-hidden="true">
    <img class="hero-photo" src="https://images.unsplash.com/photo-1511974035430-5de47d3b95da?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=7c7f3d6a0f1f2f8c8b2c5b6c3a2d1e5f" alt="Warm studio interior with candlelight and crystals">
  </div>
</section>

<!-- Main Sections -->
<div class="sections">
  <main class="main">
    <!-- Services -->
    <section id="services" class="card" aria-labelledby="services-heading">
      <h2 id="services-heading">Services</h2>
      <p style="margin: 0 0 12px; color: #5b575b;">Readings tailored to your life — honest, grounded, and compassionate.</p>
      <div class="services">
        <div class="service">
          <h4>Palmistry</h4>
          <p>20 / 40 min — Discover patterns in love, career, and timing. Immediate clarity and practical next steps.</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Book Palmistry</a></div>
        </div>
        <div class="service">
          <h4>Psychic Intuitive</h4>
          <p>30 / 60 min — Direct guidance for relationships, work, and personal growth. Gentle, accurate, and compassionate.</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Book Psychic</a></div>
        </div>
        <div class="service">
          <h4>Spiritual Remedies</h4>
          <p>Custom candles, stones, and tailored energetic practices to shift outcomes and protect your path.</p>
          <div style="margin-top: 8px;"><a href="#shop" class="btn-outline">Shop Remedies</a></div>
        </div>
        <div class="service">
          <h4>Intuitive Coaching</h4>
          <p>Actionable next steps after readings — integrate insights into daily life with supportive coaching.</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Learn More</a></div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="card" aria-labelledby="testi-heading">
      <h2 id="testi-heading">Stories from the Room</h2>
      <p style="margin: 0 0 12px; color: #5b575b;">Real experiences from guests who left lighter and clearer.</p>
      <div class="testimonials">
        <div class="testi">
          <p>"Lori made me feel so good. It was a warm, kind, and very revealing session. I'm grateful. I recommend Lori."</p>
          <p class="who">— Asi Prensa</p>
        </div>
        <div class="testi">
          <p>"She didn't just listen. They saw me, guided me, and helped me step into a version of myself I almost forgot was possible."</p>
          <p class="who">— Mirko Ballarino</p>
        </div>
        <div class="testi">
          <p>"Amazing experience — opened up my eyes a lot more! I look forward to another session."</p>
          <p class="who">— Nay Tovar</p>
        </div>
        <div class="testi">
          <p>"Immediate read on my relationships and offered paths forward to improve connections."</p>
          <p class="who">— Teresa Moore</p>
        </div>
      </div>
    </section>

    <!-- Shop -->
    <section id="shop" class="card" aria-labelledby="shop-heading">
      <h2 id="shop-heading">Shop — Curated Tools</h2>
      <p style="margin: 0 0 12px; color: #5b575b;">Candles, protective stones, and bundles chosen for clarity and protection.</p>
      <div class="shop-grid">
        <div class="prod">
          <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3" alt="Hand-poured protection candle with cedar and sage">
          <h5>Protection Candle</h5>
          <p>Hand-poured soy, calming cedar & sage • $18</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
        </div>
        <div class="prod">
          <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=800&auto=format&fit=crop" alt="Curated protective stones for grounding and clarity">
          <h5>Protection Stones</h5>
          <p>Curated set for grounding & clarity • $22</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
        </div>
        <div class="prod">
          <img src="https://images.unsplash.com/photo-1493666438817-866a91353ca9?q=80&w=800&auto=format&fit=crop" alt="Starter bundle with candle, stones, and guidance card">
          <h5>Starter Bundle</h5>
          <p>Candle + stones + guidance card • $34</p>
          <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="card" aria-labelledby="about-heading">
      <h2 id="about-heading">Meet Lori</h2>
      <div class="about-hero">
        <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3" alt="Lori portrait">
        <div>
          <p style="margin: 0 0 8px; color: #5b575b;">Lori brings compassionate clarity through palmistry and intuitive readings. Clients leave with practical guidance, renewed courage, and often a lighter heart. Her approach is warm, honest, and grounded — a trusted presence on King Street since 2019.</p>
          <p style="margin: 0;"><a href="#booking" class="btn-outline">Book with Lori</a></p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="card faq" aria-labelledby="faq-heading">
      <h3 id="faq-heading">FAQ</h3>
      <dl>
        <dt>What should I expect?</dt>
        <dd>Warm, private session focused on clarity and practical next steps — be open, bring questions if you like.</dd>
        <dt>How to prepare?</dt>
        <dd>Arrive a few minutes early, bring a short list of concerns (optional). No special attire required.</dd>
        <dt>Cancellation & refunds?</dt>
        <dd>Please notify 24 hours in advance for a full refund or to reschedule.</dd>
        <dt>Do you ship shop items?</dt>
        <dd>Yes — local pickup available, shipping across the U.S. for select items.</dd>
      </dl>
    </section>

    <!-- Contact -->
    <section id="contact" class="card" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Get in Touch</h2>
      <p style="margin: 0 0 12px; color: #5b575b;">Have questions? Reach out anytime.</p>
      <div class="contact-row">
        <div class="contact-card">
          <strong>📍 Location</strong>
          <p style="margin: 4px 0; font-size: 14px;">123 King Street, Charleston, SC 29401</p>
        </div>
        <div class="contact-card">
          <strong>📞 Phone</strong>
          <p style="margin: 4px 0; font-size: 14px;"><a href="tel:+18435551234">(843) 555-1234</a></p>
        </div>
        <div class="contact-card">
          <strong>✉️ Email</strong>
          <p style="margin: 4px 0; font-size: 14px;"><a href="mailto:hello@psychicroomonking.com">hello@psychicroomonking.com</a></p>
        </div>
      </div>
    </section>
  </main>

  <!-- Sidebar -->
  <aside class="side">
    <div class="card">
      <h4 style="margin: 0 0 8px;">Quick Booking</h4>
      <p style="margin: 0 0 12px; color: #5b575b; font-size: 14px;">Select a service and reserve your time. Secure payments via Stripe.</p>
      <div style="display: flex; flex-direction: column; gap: 8px;">
        <a href="#booking" class="cta-book" style="text-align: center;">Book a Reading</a>
        <a href="#contact" class="btn-outline" style="text-align: center;">Contact Us</a>
      </div>
    </div>

    <div class="card">
      <h4 style="margin: 0 0 8px;">Hours & Location</h4>
      <p style="margin: 0 0 6px; font-size: 14px;"><strong>📍</strong> 123 King St, Charleston, SC</p>
      <p style="margin: 0 0 6px; font-size: 14px;"><strong>🕐</strong> Tue–Sun: 11am–7pm</p>
      <p style="margin: 0 0 12px; font-size: 14px; color: #999;">Closed Mondays</p>
      <a href="https://maps.google.com/maps/place/123+King+Street,+Charleston,+SC" target="_blank" rel="noopener" class="btn-outline" style="display: block; text-align: center;">Open in Maps</a>
    </div>

    <div class="card">
      <h4 style="margin: 0 0 8px;">Reviews</h4>
      <p style="margin: 0 0 8px; color: #5b575b; font-size: 14px;">⭐ "Great experience, had lots of guidance from start to finish. Very satisfied." — Google Reviews</p>
      <a href="#testimonials" class="btn-outline" style="display: block; text-align: center;">Read more stories</a>
    </div>
  </aside>
</div>
      </nav>
      <button class="mobile-menu" aria-label="Toggle menu">☰</button>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-left">
        <div class="hero-eyebrow">✨ Clarity • Comfort • Courage</div>
        <h1 class="hero-h">Find clarity that feels like coming home</h1>
        <p class="hero-sub">Personal readings, spiritual remedies, and curated tools — honest, compassionate, and transformative. Walk-ins welcome; appointments recommended.</p>
        <div class="hero-ctas">
          <a href="#booking" class="cta-book">Book a Reading</a>
          <a href="#services" class="btn-outline">View Services</a>
        </div>
        <div class="trustbar">
          <div class="pulse">Locally loved</div>
          <div>Accurate readings • Candles & stones • Warm, private space</div>
        </div>
      </div>
      <div class="hero-right" aria-hidden="true">
        <img class="hero-photo" src="https://images.unsplash.com/photo-1511974035430-5de47d3b95da?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=7c7f3d6a0f1f2f8c8b2c5b6c3a2d1e5f" alt="Warm studio interior with candlelight and crystals">
      </div>
    </section>

    <!-- Main Sections -->
    <div class="sections">
      <main class="main">
        <!-- Services -->
        <section id="services" class="card" aria-labelledby="services-heading">
          <h2 id="services-heading">Services</h2>
          <p style="margin: 0 0 12px; color: #5b575b;">Readings tailored to your life — honest, grounded, and compassionate.</p>
          <div class="services">
            <div class="service">
              <h4>Palmistry</h4>
              <p>20 / 40 min — Discover patterns in love, career, and timing. Immediate clarity and practical next steps.</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Book Palmistry</a></div>
            </div>
            <div class="service">
              <h4>Psychic Intuitive</h4>
              <p>30 / 60 min — Direct guidance for relationships, work, and personal growth. Gentle, accurate, and compassionate.</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Book Psychic</a></div>
            </div>
            <div class="service">
              <h4>Spiritual Remedies</h4>
              <p>Custom candles, stones, and tailored energetic practices to shift outcomes and protect your path.</p>
              <div style="margin-top: 8px;"><a href="#shop" class="btn-outline">Shop Remedies</a></div>
            </div>
            <div class="service">
              <h4>Intuitive Coaching</h4>
              <p>Actionable next steps after readings — integrate insights into daily life with supportive coaching.</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Learn More</a></div>
            </div>
          </div>
        </section>

        <!-- Testimonials -->
        <section id="testimonials" class="card" aria-labelledby="testi-heading">
          <h2 id="testi-heading">Stories from the Room</h2>
          <p style="margin: 0 0 12px; color: #5b575b;">Real experiences from guests who left lighter and clearer.</p>
          <div class="testimonials">
            <div class="testi">
              <p>"Lori made me feel so good. It was a warm, kind, and very revealing session. I'm grateful. I recommend Lori."</p>
              <p class="who">— Asi Prensa</p>
            </div>
            <div class="testi">
              <p>"She didn't just listen. They saw me, guided me, and helped me step into a version of myself I almost forgot was possible."</p>
              <p class="who">— Mirko Ballarino</p>
            </div>
            <div class="testi">
              <p>"Amazing experience — opened up my eyes a lot more! I look forward to another session."</p>
              <p class="who">— Nay Tovar</p>
            </div>
            <div class="testi">
              <p>"Immediate read on my relationships and offered paths forward to improve connections."</p>
              <p class="who">— Teresa Moore</p>
            </div>
          </div>
        </section>

        <!-- Shop -->
        <section id="shop" class="card" aria-labelledby="shop-heading">
          <h2 id="shop-heading">Shop — Curated Tools</h2>
          <p style="margin: 0 0 12px; color: #5b575b;">Candles, protective stones, and bundles chosen for clarity and protection.</p>
          <div class="shop-grid">
            <div class="prod">
              <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3" alt="Hand-poured protection candle with cedar and sage">
              <h5>Protection Candle</h5>
              <p>Hand-poured soy, calming cedar & sage • $18</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
            </div>
            <div class="prod">
              <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=800&auto=format&fit=crop" alt="Curated protective stones for grounding and clarity">
              <h5>Protection Stones</h5>
              <p>Curated set for grounding & clarity • $22</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
            </div>
            <div class="prod">
              <img src="https://images.unsplash.com/photo-1493666438817-866a91353ca9?q=80&w=800&auto=format&fit=crop" alt="Starter bundle with candle, stones, and guidance card">
              <h5>Starter Bundle</h5>
              <p>Candle + stones + guidance card • $34</p>
              <div style="margin-top: 8px;"><a href="#booking" class="btn-outline">Add to cart</a></div>
            </div>
          </div>
        </section>

        <!-- About -->
        <section id="about" class="card" aria-labelledby="about-heading">
          <h2 id="about-heading">Meet Lori</h2>
          <div class="about-hero">
            <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3" alt="Lori portrait">
            <div>
              <p style="margin: 0 0 8px; color: #5b575b;">Lori brings compassionate clarity through palmistry and intuitive readings. Clients leave with practical guidance, renewed courage, and often a lighter heart. Her approach is warm, honest, and grounded — a trusted presence on King Street since 2019.</p>
              <p style="margin: 0;"><a href="#booking" class="btn-outline">Book with Lori</a></p>
            </div>
          </div>
        </section>

        <!-- FAQ -->
        <section class="card faq" aria-labelledby="faq-heading">
          <h3 id="faq-heading">FAQ</h3>
          <dl>
            <dt>What should I expect?</dt>
            <dd>Warm, private session focused on clarity and practical next steps — be open, bring questions if you like.</dd>
            <dt>How to prepare?</dt>
            <dd>Arrive a few minutes early, bring a short list of concerns (optional). No special attire required.</dd>
            <dt>Cancellation & refunds?</dt>
            <dd>Please notify 24 hours in advance for a full refund or to reschedule.</dd>
            <dt>Do you ship shop items?</dt>
            <dd>Yes — local pickup available, shipping across the U.S. for select items.</dd>
          </dl>
        </section>

        <!-- Contact -->
        <section id="contact" class="card" aria-labelledby="contact-heading">
          <h2 id="contact-heading">Get in Touch</h2>
          <p style="margin: 0 0 12px; color: #5b575b;">Have questions? Reach out anytime.</p>
          <div class="contact-row">
            <div class="contact-card">
              <strong>📍 Location</strong>
              <p style="margin: 4px 0; font-size: 14px;">123 King Street, Charleston, SC 29401</p>
            </div>
            <div class="contact-card">
              <strong>📞 Phone</strong>
              <p style="margin: 4px 0; font-size: 14px;"><a href="tel:+18435551234">(843) 555-1234</a></p>
            </div>
            <div class="contact-card">
              <strong>✉️ Email</strong>
              <p style="margin: 4px 0; font-size: 14px;"><a href="mailto:hello@psychicroomonking.com">hello@psychicroomonking.com</a></p>
            </div>
          </div>
        </section>
      </main>

      <!-- Sidebar -->
      <aside class="side">
        <div class="card">
          <h4 style="margin: 0 0 8px;">Quick Booking</h4>
          <p style="margin: 0 0 12px; color: #5b575b; font-size: 14px;">Select a service and reserve your time. Secure payments via Stripe.</p>
          <div style="display: flex; flex-direction: column; gap: 8px;">
            <a href="#booking" class="cta-book" style="text-align: center;">Book a Reading</a>
            <a href="#contact" class="btn-outline" style="text-align: center;">Contact Us</a>
          </div>
        </div>

        <div class="card">
          <h4 style="margin: 0 0 8px;">Hours & Location</h4>
          <p style="margin: 0 0 6px; font-size: 14px;"><strong>📍</strong> 123 King St, Charleston, SC</p>
          <p style="margin: 0 0 6px; font-size: 14px;"><strong>🕐</strong> Tue–Sun: 11am–7pm</p>
          <p style="margin: 0 0 12px; font-size: 14px; color: #999;">Closed Mondays</p>
          <a href="https://maps.google.com/maps/place/123+King+Street,+Charleston,+SC" target="_blank" rel="noopener" class="btn-outline" style="display: block; text-align: center;">Open in Maps</a>
        </div>

        <div class="card">
          <h4 style="margin: 0 0 8px;">Reviews</h4>
          <p style="margin: 0 0 8px; color: #5b575b; font-size: 14px;">⭐ "Great experience, had lots of guidance from start to finish. Very satisfied." — Google Reviews</p>
          <a href="#testimonials" class="btn-outline" style="display: block; text-align: center;">Read more stories</a>
        </div>
      </aside>
    </div>
  </div>

  <!-- Sticky Book Button (Mobile) -->
  <a href="#booking" <a href="tel:+1-843-555-1234" class="cta-book">Call to Book</a>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2026 Psychic Room on King. All rights reserved. | Charleston, SC</p>
  </footer>

  <script>
    // Smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });

    // Mobile menu toggle (placeholder)
    const mobileMenu = document.querySelector('.mobile-menu');
    if (mobileMenu) {
      mobileMenu.addEventListener('click', () => {
        alert('Mobile menu coming soon! For now, scroll and tap links.');
      });
    }
  </script>
</body>
</html>
