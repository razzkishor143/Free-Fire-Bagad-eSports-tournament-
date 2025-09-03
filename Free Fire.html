<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Free Fire eSports Tournament</title>
  <meta name="description" content="Join the ultimate Free Fire eSports Tournament. Register your squad, check the schedule, and compete for glory and prizes!" />
  <meta name="theme-color" content="#111827" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1020;          /* base background */
      --bg2:#0f172a;         /* panel background */
      --card:#111827cc;      /* glass card */
      --txt:#e5e7eb;         /* primary text */
      --muted:#a5b4fc;       /* secondary text */
      --brandA:#7c3aed;      /* accent 1 */
      --brandB:#22d3ee;      /* accent 2 */
      --brandC:#f59e0b;      /* accent 3 */
      --ok:#22c55e;          /* success */
      --warn:#f97316;        /* warning */
      --err:#ef4444;         /* error */
      --radius:18px;
      --shadow:0 10px 30px rgba(0,0,0,.35);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: 'Outfit', system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
      color:var(--txt);
      background: radial-gradient(1200px 800px at 20% -10%, #1e293b 0%, transparent 55%),
                  radial-gradient(900px 600px at 110% 20%, #0ea5e9 0%, transparent 50%),
                  radial-gradient(1000px 700px at -10% 90%, #7c3aed 0%, transparent 60%),
                  var(--bg);
      overflow-x:hidden;
    }

    /* ---------- Utilities ---------- */
    .container{width:min(1200px,90vw); margin-inline:auto}
    .grid{display:grid; gap:1.2rem}
    .btn{
      display:inline-flex; align-items:center; gap:.6rem; cursor:pointer;
      background: linear-gradient(135deg,var(--brandA),var(--brandB));
      color:white; border:none; padding:.9rem 1.2rem; border-radius:calc(var(--radius) - 6px);
      font-weight:700; letter-spacing:.3px; box-shadow: var(--shadow);
      transition: transform .15s ease, box-shadow .15s ease, filter .2s ease;
      text-decoration:none;
    }
    .btn:hover{transform: translateY(-2px); filter:brightness(1.05)}
    .btn:active{transform: translateY(0)}
    .badge{display:inline-block; padding:.3rem .6rem; border-radius:999px; background:#0b1225; border:1px solid #283149; color:var(--muted); font-size:.8rem}
    .card{background:linear-gradient(180deg,#0b1225CC,#0b1225AA); border:1px solid #26324d; backdrop-filter: blur(10px); border-radius:var(--radius); box-shadow: var(--shadow)}
    .sub{color:#c7d2fe}
    .accent{background:linear-gradient(135deg, #8b5cf6 0%, #22d3ee 100%); -webkit-background-clip:text; background-clip:text; color:transparent}
    .kbd{border:1px solid #374151; border-bottom-width:3px; border-radius:10px; padding:.1rem .5rem; font-size:.9rem; background:#111827; color:#e5e7eb}

    /* ---------- Navigation ---------- */
    header{
      position:sticky; top:0; z-index:50; backdrop-filter:saturate(140%) blur(10px);
      background:linear-gradient(180deg,#0b1225cc 0%, #0b122500 100%);
      border-bottom:1px solid #1f2a44aa;
    }
    .nav{display:flex; align-items:center; justify-content:space-between; padding:1rem 0}
    .brand{display:flex; align-items:center; gap:.8rem; font-weight:800; letter-spacing:.5px}
    .brand .spark{width:28px; height:28px; border-radius:8px; background:conic-gradient(from 0deg, var(--brandB), var(--brandA), var(--brandC), var(--brandB)); box-shadow:0 0 25px #22d3ee88}
    nav a{color:#c7d2fe; text-decoration:none; font-weight:600}
    .links{display:flex; gap:1rem}
    .hamburger{display:none}

    @media (max-width: 900px){
      .links{display:none}
      .hamburger{display:flex; padding:.6rem .8rem; border-radius:10px; border:1px solid #283149; background:#0b1225; color:#c7d2fe; cursor:pointer}
      .mobile{display:none; position:absolute; top:64px; left:0; right:0; background:#0b1225f2; border-bottom:1px solid #283149; padding:1rem}
      .mobile.open{display:block}
      .mobile a{display:block; padding:.8rem 0; color:#c7d2fe; text-decoration:none}
    }

    /* ---------- Hero ---------- */
    .hero{position:relative; padding: clamp(80px, 16vh, 180px) 0 80px}
    .hero .content{display:grid; grid-template-columns: 1.2fr .8fr; gap:2rem; align-items:center}
    .eyebrow{display:inline-flex; align-items:center; gap:.5rem}
    .eyebrow .dot{width:8px; height:8px; border-radius:50%; background:var(--brandB); box-shadow:0 0 12px #22d3ee}
    h1{font-size:clamp(2.2rem, 5vw, 4rem); line-height:1.05; margin:.2rem 0 .8rem}
    .lead{font-size: clamp(1rem, 1.4vw, 1.2rem); opacity:.9}
    .hero .actions{display:flex; gap:1rem; margin-top:1.2rem; flex-wrap:wrap}

    .countdown{display:grid; grid-template-columns: repeat(4, minmax(70px, 1fr)); gap:.8rem; margin-top:1.6rem}
    .time{
      text-align:center; padding:1rem; border-radius:16px; border:1px solid #27324b; background:linear-gradient(180deg,#0b1225,#0b1225c2);
    }
    .time strong{display:block; font-size:clamp(1.4rem, 3vw, 2.4rem)}
    .time span{font-size:.85rem; color:#9fb0ff}
    .hero-card{padding:1.2rem; text-align:center}

    @media (max-width: 1000px){
      .hero .content{grid-template-columns: 1fr}
    }

    /* ---------- Sections ---------- */
    section{padding:80px 0}
    section h2{font-size:clamp(1.8rem, 3.8vw, 2.6rem); margin:0 0 .6rem}
    section p.section-lead{margin:0 0 1.2rem; color:#c7d2fe}

    .features{grid-template-columns: repeat(3,1fr)}
    .feature{padding:1rem; border:1px solid #283149}
    .feature h3{margin:.4rem 0}
    .feature p{opacity:.9}
    @media (max-width: 900px){.features{grid-template-columns:1fr}}

    .schedule{grid-template-columns:1.2fr .8fr}
    .timeline{position:relative; padding-left:1.2rem}
    .timeline::before{content:""; position:absolute; left:.4rem; top:0; bottom:0; width:2px; background:#27324b}
    .event{position:relative; padding:.8rem 1rem; margin:.6rem 0; border:1px solid #283149; border-radius:14px; background:#0b1225}
    .event::before{content:""; position:absolute; left:-.25rem; top:1rem; width:10px; height:10px; border-radius:50%; background:var(--brandB); box-shadow:0 0 10px #22d3ee}
    .side-card{padding:1rem}
    @media (max-width: 1000px){.schedule{grid-template-columns:1fr}}

    .prizes{grid-template-columns: repeat(3,1fr)}
    .prize{padding:1.2rem; text-align:center; border:1px solid #283149}
    .prize .place{font-size:2rem}
    .prize .amount{font-weight:800; font-size:2.2rem}
    @media (max-width: 900px){.prizes{grid-template-columns:1fr}}

    .register{grid-template-columns:1fr 1fr}
    .register .form{padding:1rem}
    .register form{display:grid; gap:.9rem}
    .register input, .register select, .register textarea{
      width:100%; padding:0.85rem 0.9rem; background:#0c1224; border:1px solid #283149; border-radius:12px; color:#dbeafe;
    }
    .register input:focus, .register select:focus, .register textarea:focus{outline:2px solid #475569}
    .register .note{font-size:.9rem; color:#c7d2fe}
    @media (max-width: 1000px){.register{grid-template-columns:1fr}}

    .faq{grid-template-columns: 1fr 1fr}
    details{border:1px solid #283149; border-radius:14px; padding:1rem; background:#0b1225}
    details summary{cursor:pointer; font-weight:700}
    details[open]{background:#0c142a}
    @media (max-width: 900px){.faq{grid-template-columns:1fr}}

    footer{padding:60px 0; border-top:1px solid #1f2a44aa; background:linear-gradient(180deg,#0b1225ee, #0b1225f8)}
    .foot{display:grid; grid-template-columns: 1.4fr .6fr .6fr; gap:1.2rem}
    .foot a{color:#c7d2fe; text-decoration:none}
    .foot small{opacity:.8}
    @media (max-width: 900px){.foot{grid-template-columns:1fr}}

    /* ---------- Animations ---------- */
    @keyframes floaty { 0%{transform:translateY(0)} 50%{transform:translateY(-10px)} 100%{transform:translateY(0)} }
    .floaty{animation: floaty 6s ease-in-out infinite}

    .reveal{opacity:0; transform: translateY(20px); transition: all .7s ease}
    .reveal.visible{opacity:1; transform: translateY(0)}

    /* ---------- Decorative: neon separators ---------- */
    .beam{height:2px; background:linear-gradient(90deg, transparent, var(--brandB), var(--brandA), transparent); filter:blur(.2px); opacity:.8}

    /* ---------- Canvas particles backdrop ---------- */
    #space{position:fixed; inset:0; z-index:-1}
  </style>
</head>
<body>
  <canvas id="space" aria-hidden="true"></canvas>

  <!-- Header / Navigation -->
  <header>
    <div class="container nav">
      <div class="brand" aria-label="Tournament Brand">
        <div class="spark"></div>
        <span>Free Fire <span class="accent">eSports</span></span>
      </div>
      <nav class="links" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#schedule">Schedule</a>
        <a href="#prizes">Prizes</a>
        <a href="#register">Register</a>
        <a href="#faq">FAQ</a>
      </nav>
      <button class="hamburger" id="hamburger" aria-label="Open menu" aria-expanded="false">☰</button>
    </div>
    <div class="mobile" id="mobileMenu" aria-label="Mobile Menu">
      <a href="#about">About</a>
      <a href="#schedule">Schedule</a>
      <a href="#prizes">Prizes</a>
      <a href="#register">Register</a>
      <a href="#faq">FAQ</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="container content">
      <div>
        <div class="eyebrow"><span class="dot"></span><span class="badge">Squad Battle Royale</span></div>
        <h1 class="accent">Free Fire Tournament 2025</h1>
        <p class="lead">Gear up for intense action! Register your squad, battle through qualifiers, and claim the crown. Streamed live with shoutcasters and instant highlights.</p>
        <div class="actions">
          <a class="btn" href="#register">Register Team</a>
          <a class="btn" style="background:linear-gradient(135deg,var(--brandC),var(--brandB))" href="#schedule">View Schedule</a>
        </div>

        <div class="countdown" id="countdown" aria-live="polite">
          <div class="time card hero-card"><strong id="dd">00</strong><span>Days</span></div>
          <div class="time card hero-card"><strong id="hh">00</strong><span>Hours</span></div>
          <div class="time card hero-card"><strong id="mm">00</strong><span>Minutes</span></div>
          <div class="time card hero-card"><strong id="ss">00</strong><span>Seconds</span></div>
        </div>
        <p class="sub">Kickoff: <span id="kickoffText"></span></p>
      </div>

      <div class="card floaty" aria-hidden="true" style="aspect-ratio: 16/10; display:grid; place-items:center;">
        <div>
          <div class="badge">Prize Pool</div>
          <div style="font-size:clamp(2.2rem,4vw,3rem); font-weight:800; margin:.3rem 0">₹ 1,50,000</div>
          <div class="beam"></div>
          <p class="sub" style="margin-top:.6rem">LAN Finals • Anti‑Cheat • Live Stream</p>
        </div>
      </div>
    </div>
  </section>

  <div class="beam"></div>

  <!-- About / Features -->
  <section id="about">
    <div class="container">
      <h2 class="accent">Why join?</h2>
      <p class="section-lead">From grassroots squads to seasoned pros—our format is built for hype, fairness, and unforgettable moments.</p>
      <div class="grid features">
        <div class="card feature reveal">
          <span class="badge">Format</span>
          <h3>Open Qualifiers → Grand Finals</h3>
          <p>Best‑of series with point multipliers, map rotations, and fair seeding. Custom rooms with referees and replay reviews.</p>
        </div>
        <div class="card feature reveal">
          <span class="badge">Broadcast</span>
          <h3>Live Production</h3>
          <p>Multi‑camera stream, live overlays, real‑time standings, and pro shoutcasters. Highlights posted after every round.</p>
        </div>
        <div class="card feature reveal">
          <span class="badge">Integrity</span>
          <h3>Strict Anti‑Cheat</h3>
          <p>Hardware checks, POV recordings, and admin spectating. Zero tolerance policy to keep the battleground fair.</p>
        </div>
      </div>
    </div>
  </section>

  <div class="beam"></div>

  <!-- Schedule -->
  <section id="schedule">
    <div class="container grid schedule">
      <div>
        <h2 class="accent">Schedule</h2>
        <p class="section-lead">All times are in IST (UTC+5:30). Qualifiers are online; finals are on LAN.</p>
        <div class="timeline">
          <div class="event reveal"><strong>Registrations Open</strong><br><small>Sep 10, 2025 • 10:00</small></div>
          <div class="event reveal"><strong>Qualifier Weekend</strong><br><small>Oct 11–12, 2025 • 14:00–20:00</small></div>
          <div class="event reveal"><strong>Semifinals</strong><br><small>Oct 18, 2025 • 16:00</small></div>
          <div class="event reveal"><strong>Grand Finals (LAN)</strong><br><small>Oct 19, 2025 • 17:00 • Chennai</small></div>
        </div>
      </div>
      <aside class="card side-card reveal">
        <h3>Venue (LAN Finals)</h3>
        <p>Chennai Convention Centre, Hall B</p>
        <p class="sub">Spectator passes limited. Stream link shared 48h prior.</p>
        <a class="btn" href="#register">Get Team Slot</a>
      </aside>
    </div>
  </section>

  <div class="beam"></div>

  <!-- Prizes -->
  <section id="prizes">
    <div class="container">
      <h2 class="accent">Prize Pool</h2>
      <p class="section-lead">Cash rewards + in‑game diamonds and sponsor gear.</p>
      <div class="grid prizes">
        <div class="card prize reveal">
          <div class="place">🥇 1st</div>
          <div class="amount">₹80,000</div>
          <p>+ Trophy, 10,000 Diamonds, Sponsor Bundle</p>
        </div>
        <div class="card prize reveal">
          <div class="place">🥈 2nd</div>
          <div class="amount">₹40,000</div>
          <p>+ 6,000 Diamonds</p>
        </div>
        <div class="card prize reveal">
          <div class="place">🥉 3rd</div>
          <div class="amount">₹30,000</div>
          <p>+ 3,000 Diamonds</p>
        </div>
      </div>
    </div>
  </section>

  <div class="beam"></div>

  <!-- Registration -->
  <section id="register">
    <div class="container grid register">
      <div>
        <h2 class="accent">Register Your Squad</h2>
        <p class="section-lead">Limited slots. Team captains must be 16+ and provide valid in‑game IDs.</p>
        <form class="card form" id="regForm" novalidate>
          <div class="grid" style="grid-template-columns:1fr 1fr; gap:.9rem">
            <div>
              <label for="team" class="sub">Team Name</label>
              <input id="team" name="team" placeholder="e.g., Phoenix Reborn" required />
            </div>
            <div>
              <label for="region" class="sub">Region</label>
              <select id="region" name="region" required>
                <option value="" disabled selected>Select region</option>
                <option>India - North</option>
                <option>India - South</option>
                <option>India - East</option>
                <option>India - West</option>
              </select>
            </div>
          </div>

          <div class="grid" style="grid-template-columns:1fr 1fr; gap:.9rem">
            <div>
              <label for="captain" class="sub">Captain Name</label>
              <input id="captain" name="captain" placeholder="Full name" required />
            </div>
            <div>
              <label for="email" class="sub">Email</label>
              <input id="email" type="email" name="email" placeholder="captain@example.com" required />
            </div>
          </div>

          <div>
            <label for="phone" class="sub">Phone (WhatsApp)</label>
            <input id="phone" name="phone" inputmode="numeric" placeholder="10‑digit number" minlength="10" maxlength="10" required />
          </div>

          <div>
            <label class="sub">Player In‑Game IDs (5)</label>
            <textarea name="players" rows="4" placeholder="One per line (5 players incl. captain)" required></textarea>
          </div>

          <div class="grid" style="grid-template-columns:1fr 1fr; gap:.9rem">
            <div>
              <label for="mode" class="sub">Platform</label>
              <select id="mode" name="mode" required>
                <option value="" disabled selected>Select</option>
                <option>Mobile</option>
                <option>Emulator</option>
              </select>
            </div>
            <div>
              <label for="agree" class="sub">Rules</label>
              <div style="display:flex; align-items:center; gap:.6rem">
                <input type="checkbox" id="agree" required />
                <label for="agree">I agree to the tournament rules.</label>
              </div>
            </div>
          </div>

          <button class="btn" type="submit">Submit Registration</button>
          <p class="note">You'll receive a confirmation email with lobby details if selected.</p>
        </form>
      </div>

      <aside class="card form reveal">
        <h3>Entry Rules (Quick)</h3>
        <ul>
          <li>Squads of 5 (4 + 1 sub). All 5 IDs required.</li>
          <li>Use of third‑party tools/cheats → instant ban.</li>
          <li>POV recording may be requested by admins.</li>
          <li>Admins' decisions are final.</li>
        </ul>
        <p class="sub">Full rulebook available after registration.</p>
      </aside>
    </div>
  </section>

  <div class="beam"></div>

  <!-- FAQ -->
  <section id="faq">
    <div class="container">
      <h2 class="accent">FAQ</h2>
      <div class="grid faq">
        <details class="reveal"><summary>What is the entry fee?</summary>
          <p>Online qualifiers are free. Finalists pay a small LAN slot security deposit, refundable upon check‑in.</p>
        </details>
        <details class="reveal"><summary>How are teams seeded?</summary>
          <p>Randomized for qualifiers, performance‑based for playoffs using points & tiebreakers.</p>
        </details>
        <details class="reveal"><summary>Where will it be streamed?</summary>
          <p>YouTube + Facebook Live. Links shared 48 hours before matches.</p>
        </details>
        <details class="reveal"><summary>Can we swap players?</summary>
          <p>One substitution allowed before semifinals; notify admins via your confirmation email thread.</p>
        </details>
      </div>
    </div>
  </section>

  <footer>
    <div class="container foot">
      <div>
        <div class="brand" style="margin-bottom:.6rem">
          <div class="spark"></div><span>Free Fire <span class="accent">eSports</span></span>
        </div>
        <small>Unaffiliated community tournament. Free Fire is a trademark of its respective owners.</small>
      </div>
      <div>
        <strong>Contact</strong>
        <p class="sub">support@gg‑arena.example</p>
        <p class="sub">+91 90000 12345</p>
      </div>
      <div>
        <strong>Social</strong>
        <p><a href="#">YouTube</a> · <a href="#">Instagram</a> · <a href="#">Discord</a></p>
      </div>
    </div>
  </footer>

  <script>
    // --- Responsive Nav ---
    const hamburger = document.getElementById('hamburger');
    const mobileMenu = document.getElementById('mobileMenu');
    hamburger?.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      hamburger.setAttribute('aria-expanded', open ? 'true' : 'false');
    });

    // --- Scroll reveal ---
    const io = new IntersectionObserver((entries)=>{
      entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add('visible') })
    }, {threshold: .15});
    document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

    // --- Countdown ---
    const kickoff = new Date('2025-10-11T14:00:00+05:30'); // <-- CHANGE ME
    const kickoffText = document.getElementById('kickoffText');
    kickoffText.textContent = kickoff.toLocaleString('en-IN', { dateStyle:'medium', timeStyle:'short' });

    function updateCountdown(){
      const now = new Date();
      let diff = kickoff - now;
      if(diff < 0) diff = 0;
      const s = Math.floor(diff/1000);
      const d = Math.floor(s/86400);
      const h = Math.floor((s%86400)/3600);
      const m = Math.floor((s%3600)/60);
      const sec = s%60;
      document.getElementById('dd').textContent = String(d).padStart(2,'0');
      document.getElementById('hh').textContent = String(h).padStart(2,'0');
      document.getElementById('mm').textContent = String(m).padStart(2,'0');
      document.getElementById('ss').textContent = String(sec).padStart(2,'0');
    }
    updateCountdown();
    setInterval(updateCountdown, 1000);

    // --- Simple client-side form validation + demo submit ---
    const form = document.getElementById('regForm');
    form?.addEventListener('submit', (e)=>{
      e.preventDefault();
      if(!form.checkValidity()){
        alert('Please fill all required fields correctly.');
        return;
      }
      const data = Object.fromEntries(new FormData(form).entries());
      console.log('Registration:', data);
      form.reset();
      alert('Registration submitted! Check your email for confirmation.');
    });

    // --- Animated particle background (lightweight) ---
    const canvas = document.getElementById('space');
    const ctx = canvas.getContext('2d');
    let particles = [];
    const COUNT = 80;

    function resize(){ canvas.width = innerWidth; canvas.height = innerHeight }
    addEventListener('resize', resize); resize();

    function seed(){
      particles = Array.from({length: COUNT}, () => ({
        x: Math.random()*canvas.width,
        y: Math.random()*canvas.height,
        vx: (Math.random()-.5)*.3,
        vy: (Math.random()-.5)*.3,
        r: Math.random()*2 + .5,
      }));
    }
    seed();

    function step(){
      ctx.clearRect(0,0,canvas.width,canvas.height);
      for(const p of particles){
        p.x += p.vx; p.y += p.vy;
        if(p.x<0||p.x>canvas.width) p.vx*=-1;
        if(p.y<0||p.y>canvas.height) p.vy*=-1;
      }
      // draw links
      for(let i=0;i<particles.length;i++){
        for(let j=i+1;j<particles.length;j++){
          const a = particles[i], b = particles[j];
          const dx=a.x-b.x, dy=a.y-b.y, dist=Math.hypot(dx,dy);
          if(dist<120){
            const alpha = (1 - dist/120) * .5;
            const grad = ctx.createLinearGradient(a.x,a.y,b.x,b.y);
            grad.addColorStop(0,'rgba(34,211,238,'+alpha+')');
            grad.addColorStop(1,'rgba(124,58,237,'+alpha+')');
            ctx.strokeStyle = grad; ctx.lineWidth = .6; ctx.beginPath(); ctx.moveTo(a.x,a.y); ctx.lineTo(b.x,b.y); ctx.stroke();
          }
        }
      }
      // draw dots
      for(const p of particles){
        ctx.beginPath(); ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
        ctx.fillStyle = 'rgba(203,213,225,.7)'; ctx.fill();
      }
      requestAnimationFrame(step);
    }
    step();
  </script>
</body>
</html>
