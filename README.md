<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Srinivas — Digital Marketing Strategist</title>
  <meta name="description" content="Srinivas — Digital Marketing Strategist. SEO, SEM, Social Media, Paid Ads, Email Marketing & Lead Generation." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#071021;
      --card:rgba(255,255,255,0.03);
      --glass:rgba(255,255,255,0.04);
      --muted:rgba(230,240,250,0.65);
      --accent1:#06b6d4; /* teal */
      --accent2:#7c3aed; /* purple */
      --maxw:1100px;
      --radius:14px;
      --glass-border:rgba(255,255,255,0.06);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;color:#eaf6fb;background:linear-gradient(180deg,#041425 0%, #071021 100%);-webkit-font-smoothing:antialiased}
    a{color:inherit}
    .wrap{max-width:var(--maxw);margin:36px auto;padding:22px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:14px}
    .logo{
      width:56px;height:56px;border-radius:12px;
      background:linear-gradient(135deg,var(--accent1),var(--accent2));
      display:flex;align-items:center;justify-content:center;color:#031924;font-weight:800;font-size:18px;
      box-shadow:0 6px 20px rgba(7,20,30,0.6);
    }
    nav{display:flex;gap:14px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;font-weight:600;padding:8px;border-radius:10px}
    nav a:hover{color:white;background:rgba(255,255,255,0.02)}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:28px;margin-top:28px;align-items:center}
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid var(--glass-border);
      padding:22px;border-radius:var(--radius);
      backdrop-filter: blur(8px);
      box-shadow: 0 6px 30px rgba(2,8,12,0.6);
    }
    h1{margin:0;font-size:30px}
    p.lead{color:var(--muted);margin-top:12px;line-height:1.6}
    .cta{margin-top:18px}
    .btn{
      display:inline-block;padding:10px 16px;border-radius:10px;
      background:linear-gradient(90deg,var(--accent1),var(--accent2));
      color:#02161a;font-weight:700;text-decoration:none;transition:transform .18s ease, box-shadow .18s;
      box-shadow:0 8px 24px rgba(12,18,40,0.3);
    }
    .btn:hover{transform:translateY(-4px)}
    .ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted);padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700}
    .skills{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}
    .skill{background:rgba(255,255,255,0.02);padding:8px 12px;border-radius:999px;color:var(--muted);font-weight:600;font-size:13px}
    .profile-card{display:flex;flex-direction:column;gap:12px;align-items:center;text-align:center}
    .avatar{
      width:140px;height:140px;border-radius:18px;
      background:linear-gradient(135deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      display:flex;align-items:center;justify-content:center;font-size:42px;font-weight:800;color:#eaffff;
      border:1px solid rgba(255,255,255,0.03);
    }
    .stats{display:flex;gap:12px;margin-top:8px}
    .stat{background:rgba(255,255,255,0.02);padding:10px 12px;border-radius:10px;text-align:center}
    section{margin-top:28px}
    .projects{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    .project{padding:16px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03);transition:transform .18s ease, box-shadow .18s}
    .project:hover{transform:translateY(-6px);box-shadow:0 18px 40px rgba(7,20,30,0.6)}
    .project h3{margin:0;font-size:16px}
    .services-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    .testimonial{padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(255,255,255,0.008));border:1px solid rgba(255,255,255,0.02)}
    .contact-grid{display:grid;grid-template-columns:1fr 360px;gap:14px}
    input,textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit;font-size:14px}
    .socials{display:flex;gap:10px;margin-top:12px}
    .socials a{padding:8px 10px;border-radius:10px;background:rgba(255,255,255,0.02);color:var(--muted);text-decoration:none;font-weight:700}
    footer{margin-top:36px;padding:18px;text-align:center;color:var(--muted);font-size:14px}
    /* Responsive */
    @media (max-width:1000px){.hero{grid-template-columns:1fr;}.projects{grid-template-columns:repeat(2,1fr)}.services-grid{grid-template-columns:repeat(2,1fr)}.contact-grid{grid-template-columns:1fr}}
    @media (max-width:640px){.projects{grid-template-columns:1fr}.services-grid{grid-template-columns:1fr}.wrap{padding:16px;margin:12px}}
    /* subtle entrance */
    .fade-up{opacity:0;transform:translateY(8px);animation:fadeUp .6s forwards}
    @keyframes fadeUp{to{opacity:1;transform:none}}
    /* small utilities */
    .muted{color:var(--muted)}
    .caps{font-size:12px;text-transform:uppercase;letter-spacing:1px;color:var(--muted);font-weight:700}
  </style>
  <style>    .form-group {
      position: relative;
      margin: 20px 0;
      width: 250px;
    }

    .form-input {
      width: 352px;
      height: 56px;
      padding: 12px 8px;
      border: 1px solid #ccc;
      border-radius: 6px;
      outline: none;
      font-size: 1rem;
    }

    label {
      position: absolute;
      left: 10px;
      top: 12px;
      background: #fff;
      padding: 0 5px;
      color: #888;
      font-size: 16px;
      transition: 0.3s ease;
      pointer-events: none;
    }

    /* Floating effect */
    .form-input:focus + label,
    .form-input:not(:placeholder-shown) + label {
      top: -8px;
      font-size: 0.75rem;
      color: transparent;
    
    }</style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">RS</div>
        <div>
          <div style="font-weight:800;font-size:18px">Srinivas</div>
          <div style="font-size:13px;color:var(--muted)">Digital Marketing Strategist</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#services">Services</a>
        <a href="#ClientReviews">ClientReviews</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="card fade-up" id="about">
          <h1>Hi — I'm Srinivas</h1>
          <p class="lead">I help service businesses grow predictable revenue through SEO, SEM, social media and data-driven paid ad campaigns. I design marketing funnels, run ROI-focused paid media, and build email programs that convert prospects into customers.</p>

          <div class="skills" aria-hidden>
            <div class="skill">SEO & SEM</div>
            <div class="skill">Social Media Management</div>
            <div class="skill">Paid Ad Campaigns</div>
            <div class="skill">Email Marketing</div>
            <div class="skill">Content Strategy</div>
            <div class="skill">Analytics & Reporting</div>
            <div class="skill">Lead Generation</div>
          </div>

          <div class="cta">
            <a class="btn" href="#contact">Work With Me</a>
            <a class="ghost" href="#projects" style="margin-left:10px">View case studies</a>
          </div>

          <div style="margin-top:18px;color:var(--muted);font-size:13px">
            <strong>Availability:</strong> Freelance & consulting — based in India.
          </div>
        </div>

        <aside class="card profile-card fade-up" style="align-self:start">
          <!-- Replace with your real profile image by swapping the div for an <img> -->
          <div class="avatar" aria-hidden><img src="assets\profile.png"style="width:150px;height:150px;border-radius:18px;"></div>

          <div style="font-weight:900">Srinivas</div>
          <div class="muted" style="font-size:13px">Digital Marketing Strategist</div>

          <div class="stats" role="list">
            <div class="stat" role="listitem"><div style="font-weight:800">+1.5</div><div style="font-size:12px;color:var(--muted)">Years experience</div></div>
            <div class="stat" role="listitem"><div style="font-weight:800">4</div><div style="font-size:12px;color:var(--muted)">Campaigns & Projects</div></div>
          </div>

          <div style="margin-top:8px">
            <a href="mailto:rangubuktasrinivas@gmail.com" style="text-decoration:none;color:var(--muted);font-weight:700">rangubuktasrinivas@gmail.com</a>
            <div style="font-size:13px;color:var(--muted);margin-top:6px">Phone: +91 9492727646</div>
          </div>

          <div style="margin-top:12px">
            <a class="ghost" href="#" style="display:inline-block">Download CV</a>
          </div>
        </aside>
      </section>

      <!-- Projects / Case studies -->
      <section id="projects" class="fade-up">
        <h2 style="margin-bottom:12px">Projects / Case Studies</h2>
        <div class="projects" role="list">
          <article class="project" role="listitem">
            <h3>Jathara Events — Instagram growth & lead gen</h3>
            <p class="muted" style="font-size:14px;margin-top:8px">30-day Instagram growth plan, content calendar, reels strategy and conversion-focused CTAs that increased qualified leads from social. Scope: content, scheduling, ad funnel setup.</p>
            <p style="font-size:13px;color:var(--muted);margin-top:8px"><strong>Outcome:</strong> +80% followers, +10 leads/mo (replace with your real metrics).</p>
          </article>

          <article class="project" role="listitem">
            <h3>Multi-channel paid campaign — Service business</h3>
            <p class="muted" style="font-size:14px;margin-top:8px">Ran search + social + display campaigns for a service provider, with landing page optimisation and analytics tracking across the funnel.</p>
            <p style="font-size:13px;color:var(--muted);margin-top:8px"><strong>Outcome:</strong> Improved CPL by 80% and increased conversion rate by 90%.</p>
          </article>

          <article class="project" role="listitem">
            <h3>30-day SEO sprint — On-page & technical</h3>
            <p class="muted" style="font-size:14px;margin-top:8px">Focused 30-day SEO optimization: keyword mapping, on-page content, technical fixes and local citations to lift organic visibility.</p>
            <p style="font-size:13px;color:var(--muted);margin-top:8px"><strong>Outcome:</strong> Notable increase in organic sessions and ranking improvements for target keywords.</p>
          </article>
        </div>
      </section>

      <!-- Services -->
      <section id="services" class="fade-up">
        <h2 style="margin-bottom:12px">Services</h2>
        <div class="services-grid">
          <div class="card">
            <strong>Search Engine Optimization</strong>
            <p class="muted" style="margin-top:8px;font-size:14px">Keyword research, on-page & technical SEO, content strategy and local SEO to drive qualified organic traffic.</p>
          </div>
          <div class="card">
            <strong>Social Media Marketing</strong>
            <p class="muted" style="margin-top:8px;font-size:14px">Content calendars, community growth, reels & short-form strategies tailored to your audience and goals.</p>
          </div>
          <div class="card">
            <strong>Paid Advertising</strong>
            <p class="muted" style="margin-top:8px;font-size:14px">ROI-focused campaigns across Google Ads, Facebook/Instagram and YouTube with conversion tracking and optimisation.</p>
          </div>
          <div class="card">
            <strong>Email Marketing</strong>
            <p class="muted" style="margin-top:8px;font-size:14px">Lifecycle campaigns, newsletters, and automation that convert leads into repeat customers.</p>
          </div>
          <div class="card">
            <strong>Marketing </strong>
            <p class="muted" style="margin-top:8px;font-size:14px">Full-Marketing strategy: awareness → acquisition → activation → retention. Landing pages, CRO and A/B testing.</p>
          </div>
          <div class="card">
            <strong>Analytics & Reporting</strong>
            <p class="muted" style="margin-top:8px;font-size:14px">Custom dashboards, goal setup and weekly/monthly reporting with actionable recommendations.</p>
          </div>
        </div>
      </section>

      <!-- ClientReviews -->
      <section id="ClientReviews" class="fade-up">
        <h2 style="margin-bottom:12px">ClientReviews</h2>
        <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px">
          <div class="ClientReviews">
            <div style="font-weight:700">“Srinivas delivered measurable results quickly — our leads doubled in two months.”</div>
            <div class="muted" style="margin-top:8px">— Verendhra, Service Business</div>
          </div>
          <div class="ClientReviews">
            <div style="font-weight:700">“Great communication and clear strategy. Highly recommended for SMBs.”</div>
            <div class="muted" style="margin-top:8px">— Sai, Social media handling</div>
          </div>
          <div class="ClientReviews">
            <div style="font-weight:700">“Excellent ad optimisation and reporting — the CPL dropped 30%.”</div>
            <div class="muted" style="margin-top:8px">— Ramesh, Logo design</div>
          </div>
        </div>
      </section>

      <!-- Contact -->
      <section id="contact" class="fade-up">
        <h2 style="margin-bottom:12px">Contact</h2>
        <div class="contact-grid">
          <form class="card" action="https://formspree.io/f/mzzvqyae" method="POST">
  <label class="caps" style="background-color: transparent;">Message me</label>
  
  <div class="form-group">
    <input type="text" class="form-input" name="name" placeholder="" required>
    <label style="background-color: transparent;">Your Name</label>
  </div>

  <div class="form-group">
    <input type="email" class="form-input" name="email" placeholder="" required>
    <label style="background-color: transparent;">Email</label>
  </div>

  <div class="form-group">
    <input type="text" class="form-input" name="subject" placeholder="" required>
    <label style="background-color: transparent;">Subject</label>
  </div>

  <textarea name="message" rows="6" placeholder="Tell me about your project..." required></textarea>

  <div style="display:flex;gap:8px;margin-top:10px">
    <button type="submit" class="btn">Send Email</button>
  </div>
</form>


          <aside class="card">
            <h3 style="margin:0">Quick details</h3>
            <p class="muted" style="margin-top:8px">Based in India • Available for freelance & consulting</p>
            <p style="margin-top:6px"><strong>Email:</strong> <a href="mailto:rangubuktasrinivas@gmail.com" class="muted">rangubuktasrinivas@gmail.com</a></p>
            <p><strong>Phone:</strong> <span class="muted">+91 9492727646</span></p>

            <div style="margin-top:12px">
              <strong style="font-size:13px">Social</strong>
              <div class="socials" aria-hidden>
                <a href="https://www.linkedin.com/in/srinivas-rangubukta-4a412b27b/" target="_blank">LinkedIn</a>
                <a href="https://www.instagram.com/meow___z/" target="_blank">Instagram</a>
                <a href="#" title="YouTube">YouTube</a>
              </div>
            </div>

            <div style="margin-top:14px">
              <strong class="caps">Want to know more?</strong>
              <p class="muted" style="font-size:13px;margin-top:6px">See my LinkedIn for full qualifications & experience — add your profile link here to link directly.</p>
            </div>
          </aside>
        </div>
      </section>

      <footer>
        <div style="display:flex;align-items:center;justify-content:center;gap:10px;flex-wrap:wrap">
          <div style="font-weight:700">Srinivas</div>
          <div class="muted">• Digital Marketing Strategist •</div>
          <div class="muted">© <span id="year"></span> Srinivas • All rights reserved</div>
        </div>
      </footer>
    </main>
  </div>

  <script>
    // small UX niceties
    document.getElementById('year').textContent = new Date().getFullYear();

    // smooth scroll for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', function(e){
        const target = document.querySelector(this.getAttribute('href'));
        if(target){
          e.preventDefault();
          target.scrollIntoView({behavior:'smooth',block:'start'});
        }
      });
    });

    // simple fade-up entrance
    document.querySelectorAll('.fade-up').forEach((el, i)=>{
      el.style.animationDelay = (i*80)+'ms';
    });
  </script>
</body>
</html>
