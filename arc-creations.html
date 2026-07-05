<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ARC CREATIONS – Photography & Videography</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Montserrat:wght@200;300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #C9A84C; --gold-light: #E8C97A; --gold-pale: #F5E6C0;
    --cream: #FDFAF4; --white: #FFFFFF; --dark: #1A1A1A;
    --gray: #6B6B6B; --gold-border: rgba(201,168,76,0.3);
  }
  * { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior:smooth; }
  body { font-family:'Montserrat',sans-serif; background:var(--cream); color:var(--dark); overflow-x:hidden; cursor:none; }

  .cursor { width:8px; height:8px; background:var(--gold); border-radius:50%; position:fixed; pointer-events:none; z-index:9999; transform:translate(-50%,-50%); transition:transform .15s ease; }
  .cursor-ring { width:32px; height:32px; border:1px solid var(--gold); border-radius:50%; position:fixed; pointer-events:none; z-index:9998; transform:translate(-50%,-50%); }

  body::before { content:''; position:fixed; inset:0; background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.025'/%3E%3C/svg%3E"); pointer-events:none; z-index:1; opacity:.5; }

  nav { position:fixed; top:0; left:0; right:0; z-index:100; padding:24px 60px; display:flex; justify-content:space-between; align-items:center; background:rgba(253,250,244,.88); backdrop-filter:blur(14px); border-bottom:1px solid var(--gold-border); }
  .nav-logo { font-family:'Cormorant Garamond',serif; font-size:22px; font-weight:600; letter-spacing:6px; color:var(--dark); text-decoration:none; }
  .nav-logo span { color:var(--gold); }
  .nav-links { display:flex; gap:40px; list-style:none; }
  .nav-links a { font-size:10px; letter-spacing:3px; text-transform:uppercase; color:var(--gray); text-decoration:none; transition:color .3s; font-weight:400; }
  .nav-links a:hover { color:var(--gold); }
  .nav-book { font-size:10px; letter-spacing:3px; text-transform:uppercase; background:transparent; border:1px solid var(--gold); color:var(--gold); padding:10px 24px; cursor:none; text-decoration:none; transition:all .3s; font-family:'Montserrat',sans-serif; font-weight:400; }
  .nav-book:hover { background:var(--gold); color:var(--white); }

  .hero { min-height:100vh; display:flex; align-items:center; justify-content:center; position:relative; overflow:hidden; padding:120px 60px 60px; }
  .hero-bg-lines { position:absolute; inset:0; background-image:linear-gradient(rgba(201,168,76,.06) 1px,transparent 1px),linear-gradient(90deg,rgba(201,168,76,.06) 1px,transparent 1px); background-size:80px 80px; }
  .hero-content { text-align:center; position:relative; z-index:2; max-width:700px; }
  .hero-eyebrow { font-size:10px; letter-spacing:6px; text-transform:uppercase; color:var(--gold); margin-bottom:24px; font-weight:300; opacity:0; animation:fadeUp 1s .3s forwards; }
  .hero-title { font-family:'Cormorant Garamond',serif; font-size:clamp(60px,9vw,118px); font-weight:300; line-height:.9; letter-spacing:-2px; color:var(--dark); opacity:0; animation:fadeUp 1s .5s forwards; }
  .hero-title .gold { color:var(--gold); font-style:italic; }
  .hero-sub { font-size:11px; letter-spacing:4px; text-transform:uppercase; color:var(--gray); margin-top:32px; font-weight:300; opacity:0; animation:fadeUp 1s .7s forwards; }
  .hero-divider { width:60px; height:1px; background:var(--gold); margin:28px auto; opacity:0; animation:fadeUp 1s .9s forwards; }
  .hero-desc { font-family:'Cormorant Garamond',serif; font-size:18px; color:var(--gray); font-style:italic; font-weight:300; opacity:0; animation:fadeUp 1s 1.1s forwards; line-height:1.8; }
  .hero-cta { margin-top:44px; display:flex; gap:20px; justify-content:center; flex-wrap:wrap; opacity:0; animation:fadeUp 1s 1.3s forwards; }
  .btn-primary { padding:16px 44px; background:var(--gold); color:var(--white); text-decoration:none; font-size:10px; letter-spacing:4px; text-transform:uppercase; font-weight:500; transition:all .3s; position:relative; overflow:hidden; }
  .btn-primary::after { content:''; position:absolute; inset:0; background:rgba(255,255,255,.15); transform:translateX(-100%); transition:transform .3s; }
  .btn-primary:hover::after { transform:translateX(0); }
  .btn-secondary { padding:16px 44px; border:1px solid var(--gold-border); color:var(--dark); text-decoration:none; font-size:10px; letter-spacing:4px; text-transform:uppercase; font-weight:400; transition:all .3s; }
  .btn-secondary:hover { border-color:var(--gold); color:var(--gold); }

  .camera-wrap { position:absolute; right:3%; top:50%; transform:translateY(-50%); width:420px; height:420px; z-index:3; opacity:0; animation:fadeIn 1.5s 1.5s forwards; }
  #cameraCanvas { width:100%; height:100%; }

  .marquee-section { padding:32px 0; background:var(--gold); overflow:hidden; position:relative; z-index:2; }
  .marquee-track { display:flex; gap:60px; animation:marquee 20s linear infinite; white-space:nowrap; }
  .marquee-item { font-family:'Cormorant Garamond',serif; font-size:18px; font-weight:300; color:var(--cream); letter-spacing:3px; text-transform:uppercase; flex-shrink:0; font-style:italic; }
  .marquee-dot { color:rgba(253,250,244,.4); font-style:normal; }

  .section { padding:120px 60px; position:relative; z-index:2; }
  .section-label { font-size:10px; letter-spacing:5px; text-transform:uppercase; color:var(--gold); margin-bottom:16px; font-weight:300; }
  .section-title { font-family:'Cormorant Garamond',serif; font-size:clamp(36px,5vw,60px); font-weight:300; line-height:1.1; color:var(--dark); margin-bottom:20px; }
  .section-title em { color:var(--gold); font-style:italic; }

  .services-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:2px; margin-top:60px; }
  .service-card { background:var(--white); padding:52px 40px; position:relative; overflow:hidden; transition:all .4s; border:1px solid rgba(201,168,76,.1); }
  .service-card::before { content:''; position:absolute; bottom:0; left:0; width:100%; height:2px; background:var(--gold); transform:scaleX(0); transform-origin:left; transition:transform .4s; }
  .service-card:hover { transform:translateY(-4px); box-shadow:0 20px 60px rgba(201,168,76,.1); }
  .service-card:hover::before { transform:scaleX(1); }
  .service-icon { font-size:32px; margin-bottom:24px; display:block; }
  .service-num { font-family:'Cormorant Garamond',serif; font-size:48px; font-weight:300; color:rgba(201,168,76,.15); position:absolute; top:20px; right:30px; }
  .service-title { font-family:'Cormorant Garamond',serif; font-size:26px; font-weight:400; color:var(--dark); margin-bottom:16px; }
  .service-desc { font-size:12px; line-height:2; color:var(--gray); font-weight:300; }

  .about-grid { display:grid; grid-template-columns:1fr 1fr; gap:80px; align-items:center; }
  .about-visual { position:relative; }
  .about-frame { width:100%; aspect-ratio:4/5; background:linear-gradient(135deg,var(--gold-pale),var(--white)); border:1px solid var(--gold-border); position:relative; overflow:hidden; }
  .about-frame::after { content:''; position:absolute; inset:20px; border:1px solid var(--gold-border); }
  .about-frame-inner { position:absolute; inset:0; display:flex; align-items:center; justify-content:center; flex-direction:column; gap:12px; }
  .af-icon { font-size:56px; opacity:.3; }
  .af-text { font-family:'Cormorant Garamond',serif; font-size:14px; letter-spacing:4px; text-transform:uppercase; color:var(--gold); opacity:.6; }
  .about-accent { position:absolute; bottom:-20px; right:-20px; width:120px; height:120px; border:1px solid var(--gold); z-index:-1; }
  .about-p { font-size:13px; line-height:2.2; color:var(--gray); margin-bottom:20px; font-weight:300; }
  .stats { display:flex; gap:40px; margin-top:40px; padding-top:40px; border-top:1px solid var(--gold-border); }
  .stat-num { font-family:'Cormorant Garamond',serif; font-size:44px; font-weight:300; color:var(--gold); line-height:1; }
  .stat-label { font-size:9px; letter-spacing:3px; text-transform:uppercase; color:var(--gray); margin-top:6px; font-weight:300; }

  .contact-section { background:var(--dark); padding:120px 60px; position:relative; z-index:2; overflow:hidden; }
  .contact-section::before { content:'ARC'; position:absolute; font-family:'Cormorant Garamond',serif; font-size:300px; font-weight:700; color:rgba(201,168,76,.04); top:50%; left:50%; transform:translate(-50%,-50%); pointer-events:none; white-space:nowrap; }
  .contact-grid { display:grid; grid-template-columns:1fr 1fr; gap:80px; align-items:start; position:relative; z-index:2; }
  .contact-section .section-label { color:var(--gold-light); }
  .contact-section .section-title { color:var(--white); }
  .contact-desc { font-size:13px; line-height:2; color:rgba(255,255,255,.45); margin-top:20px; font-weight:300; }
  .contact-items { margin-top:48px; display:flex; flex-direction:column; gap:28px; }
  .contact-item { display:flex; align-items:flex-start; gap:20px; }
  .ci-icon { width:44px; height:44px; border:1px solid rgba(201,168,76,.3); display:flex; align-items:center; justify-content:center; font-size:18px; flex-shrink:0; color:var(--gold); }
  .ci-label { font-size:9px; letter-spacing:3px; text-transform:uppercase; color:rgba(255,255,255,.3); margin-bottom:6px; font-weight:300; }
  .ci-value { font-family:'Cormorant Garamond',serif; font-size:18px; color:var(--white); font-weight:300; text-decoration:none; transition:color .3s; }
  .ci-value:hover { color:var(--gold); }
  .contact-right { padding-top:60px; }
  .book-card { border:1px solid rgba(201,168,76,.2); padding:52px; text-align:center; position:relative; overflow:hidden; }
  .book-card::before { content:''; position:absolute; inset:0; background:linear-gradient(135deg,rgba(201,168,76,.05),transparent); }
  .book-title { font-family:'Cormorant Garamond',serif; font-size:36px; font-weight:300; color:var(--white); margin-bottom:12px; position:relative; }
  .book-sub { font-size:11px; letter-spacing:3px; color:rgba(255,255,255,.35); text-transform:uppercase; margin-bottom:36px; font-weight:300; position:relative; }
  .btn-book { display:inline-block; padding:18px 52px; background:var(--gold); color:var(--dark); text-decoration:none; font-size:10px; letter-spacing:4px; text-transform:uppercase; font-weight:600; transition:all .3s; position:relative; font-family:'Montserrat',sans-serif; }
  .btn-book:hover { background:var(--gold-light); transform:translateY(-2px); box-shadow:0 10px 40px rgba(201,168,76,.3); }

  footer { background:#0F0F0F; padding:40px 60px; display:flex; justify-content:space-between; align-items:center; border-top:1px solid rgba(201,168,76,.15); position:relative; z-index:2; }
  .footer-logo { font-family:'Cormorant Garamond',serif; font-size:18px; letter-spacing:5px; color:var(--white); font-weight:300; }
  .footer-logo span { color:var(--gold); }
  .footer-copy { font-size:10px; color:rgba(255,255,255,.2); letter-spacing:2px; font-weight:300; }
  .footer-insta { display:flex; align-items:center; gap:10px; color:var(--gold); text-decoration:none; font-size:11px; letter-spacing:2px; transition:opacity .3s; }
  .footer-insta:hover { opacity:.7; }

  @keyframes fadeUp { from{opacity:0;transform:translateY(30px)} to{opacity:1;transform:translateY(0)} }
  @keyframes fadeIn { from{opacity:0} to{opacity:1} }
  @keyframes marquee { from{transform:translateX(0)} to{transform:translateX(-50%)} }
  .reveal { opacity:0; transform:translateY(40px); transition:opacity .8s ease,transform .8s ease; }
  .reveal.visible { opacity:1; transform:translateY(0); }

  @media(max-width:900px){
    nav{padding:20px 24px} .nav-links{display:none}
    .hero{padding:100px 24px 60px} .camera-wrap{display:none}
    .section{padding:80px 24px} .services-grid{grid-template-columns:1fr;gap:16px}
    .about-grid,.contact-grid{grid-template-columns:1fr}
    footer{flex-direction:column;gap:16px;text-align:center;padding:32px 24px}
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<nav>
  <a href="#" class="nav-logo">ARC <span>✦</span> CREATIONS</a>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a href="mailto:arccreations.18@gmail.com?subject=Book%20My%20Shoot%20%E2%80%93%20ARC%20CREATIONS&body=Hello%20ARC%20CREATIONS%2C%0A%0AI%20would%20like%20to%20book%20a%20shoot.%0A%0AName%3A%0ADate%3A%0AType%20of%20shoot%3A%0AMessage%3A" class="nav-book">Book a Shoot</a>
</nav>

<section class="hero">
  <div class="hero-bg-lines"></div>
  <div class="hero-content">
    <p class="hero-eyebrow">Photography & Videography Studio</p>
    <h1 class="hero-title">ARC<br><span class="gold">Creations</span></h1>
    <div class="hero-divider"></div>
    <p class="hero-sub">Capturing moments — Crafting stories</p>
    <p class="hero-desc">Every frame tells a story. Every story deserves<br>to be told with elegance.</p>
    <div class="hero-cta">
      <a href="mailto:arccreations.18@gmail.com?subject=Book%20My%20Shoot%20%E2%80%93%20ARC%20CREATIONS&body=Hello%20ARC%20CREATIONS%2C%0A%0AI%20would%20like%20to%20book%20a%20shoot.%0A%0AName%3A%0ADate%3A%0AType%20of%20shoot%3A%0AMessage%3A" class="btn-primary">Book Your Shoot</a>
      <a href="#services" class="btn-secondary">Explore Services</a>
    </div>
  </div>
  <div class="camera-wrap">
    <canvas id="cameraCanvas"></canvas>
  </div>
</section>

<div class="marquee-section">
  <div class="marquee-track">
    <span class="marquee-item">Photography <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Videography <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Portrait Sessions <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Events <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Short Films <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Brand Shoots <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Photography <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Videography <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Portrait Sessions <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Events <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Short Films <span class="marquee-dot">✦</span></span>
    <span class="marquee-item">Brand Shoots <span class="marquee-dot">✦</span></span>
  </div>
</div>

<section class="section" id="services">
  <div class="reveal">
    <p class="section-label">What We Do</p>
    <h2 class="section-title">Our <em>Services</em></h2>
  </div>
  <div class="services-grid">
    <div class="service-card reveal">
      <span class="service-num">01</span><span class="service-icon">📷</span>
      <h3 class="service-title">Photography</h3>
      <p class="service-desc">From intimate portraits to sweeping landscapes — we capture authentic emotion and beauty in every single frame with a timeless, editorial eye.</p>
    </div>
    <div class="service-card reveal">
      <span class="service-num">02</span><span class="service-icon">🎬</span>
      <h3 class="service-title">Videography</h3>
      <p class="service-desc">Cinematic storytelling that moves. We craft compelling visual narratives — from brand films to personal stories — that linger long after the final frame.</p>
    </div>
    <div class="service-card reveal">
      <span class="service-num">03</span><span class="service-icon">✨</span>
      <h3 class="service-title">Events & Reels</h3>
      <p class="service-desc">Weddings, launches, milestones — we document your most treasured events with precision, artistry, and an unobtrusive creative presence.</p>
    </div>
  </div>
</section>

<section class="section" id="about" style="background:var(--white)">
  <div class="about-grid">
    <div class="about-visual reveal">
      <div class="about-frame"><div class="about-frame-inner"><span class="af-icon">🎞️</span><span class="af-text">ARC Creations</span></div></div>
      <div class="about-accent"></div>
    </div>
    <div class="about-text reveal">
      <p class="section-label">Our Story</p>
      <h2 class="section-title">Art Through<br><em>Every Lens</em></h2>
      <p class="about-p">ARC Creations was born from a deep love of visual storytelling. We believe that photography and videography are not just crafts — they are languages that speak directly to the soul.</p>
      <p class="about-p">Every shoot is approached with intention, creativity, and an uncompromising commitment to quality. We don't just take photos — we create art that stands the test of time.</p>
      <div class="stats">
        <div><div class="stat-num">∞</div><div class="stat-label">Stories Told</div></div>
        <div><div class="stat-num">100%</div><div class="stat-label">Dedication</div></div>
        <div><div class="stat-num">1✦</div><div class="stat-label">Unique Vision</div></div>
      </div>
    </div>
  </div>
</section>

<section class="contact-section" id="contact">
  <div class="contact-grid">
    <div>
      <p class="section-label reveal">Get In Touch</p>
      <h2 class="section-title reveal">Let's Create<br><em style="color:var(--gold-light)">Something</em><br>Beautiful</h2>
      <p class="contact-desc reveal">Ready to tell your story? Reach out and let's create something extraordinary together.</p>
      <div class="contact-items reveal">
        <div class="contact-item">
          <div class="ci-icon">✉</div>
          <div><div class="ci-label">Email Us</div><a href="mailto:arccreations.18@gmail.com" class="ci-value">arccreations.18@gmail.com</a></div>
        </div>
        <div class="contact-item">
          <div class="ci-icon">📸</div>
          <div><div class="ci-label">Instagram</div><a href="https://instagram.com/arc.creations_" target="_blank" class="ci-value">@arc.creations_</a></div>
        </div>
        <div class="contact-item">
          <div class="ci-icon">☎</div>
          <div><div class="ci-label">Call Us</div><a href="tel:+19194430983" class="ci-value">+1 9194430983</a></div>
        </div>
      </div>
    </div>
    <div class="contact-right reveal">
      <div class="book-card">
        <h3 class="book-title">Book Your Shoot</h3>
        <p class="book-sub">Photography & Videography Sessions</p>
        <a href="mailto:arccreations.18@gmail.com?subject=Book%20My%20Shoot%20%E2%80%93%20ARC%20CREATIONS&body=Hello%20ARC%20CREATIONS%2C%0A%0AI%20would%20like%20to%20book%20a%20session.%0A%0AName%3A%0ADate%20%2F%20Time%3A%0AType%20of%20shoot%3A%0ALocation%20preference%3A%0AAdditional%20notes%3A" class="btn-book">Book Now →</a>
        <p style="margin-top:24px;font-size:10px;color:rgba(255,255,255,.2);letter-spacing:2px;position:relative;">CLICK TO SEND US AN EMAIL</p>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-logo">ARC <span>✦</span> CREATIONS</div>
  <div class="footer-copy">© 2025 ARC CREATIONS — All Rights Reserved</div>
  <a href="https://instagram.com/arc.creations_" target="_blank" class="footer-insta"><span>📸</span><span>@arc.creations_</span></a>
</footer>

<script>
// ── SMOOTH CURSOR ─────────────────────────────────────────────
const cursorDot  = document.getElementById('cursor');
const cursorRing = document.getElementById('cursorRing');
let mx=0, my=0, rx=0, ry=0;
document.addEventListener('mousemove', e => { mx=e.clientX; my=e.clientY; });
(function loop(){
  cursorDot.style.left=mx+'px'; cursorDot.style.top=my+'px';
  rx+=(mx-rx)*.13; ry+=(my-ry)*.13;
  cursorRing.style.left=rx+'px'; cursorRing.style.top=ry+'px';
  requestAnimationFrame(loop);
})();
document.querySelectorAll('a,button').forEach(el=>{
  el.addEventListener('mouseenter',()=>{ cursorDot.style.transform='translate(-50%,-50%) scale(2.5)'; cursorRing.style.transform='translate(-50%,-50%) scale(1.6)'; });
  el.addEventListener('mouseleave',()=>{ cursorDot.style.transform='translate(-50%,-50%) scale(1)';   cursorRing.style.transform='translate(-50%,-50%) scale(1)'; });
});

// ── SCROLL REVEAL ─────────────────────────────────────────────
const revObs = new IntersectionObserver(entries=>{
  entries.forEach((e,i)=>{ if(e.isIntersecting) setTimeout(()=>e.target.classList.add('visible'),i*80); });
},{threshold:.1});
document.querySelectorAll('.reveal').forEach(el=>revObs.observe(el));

// ── CANVAS CAMERA ─────────────────────────────────────────────
const canvas = document.getElementById('cameraCanvas');
const ctx    = canvas.getContext('2d');
canvas.width = 420; canvas.height = 420;

const GOLD  = '#C9A84C';
const GOLDL = '#E8C97A';
const GOLDD = '#A07828';

// ── GOLD ORBITING STRUCTURE ───────────────────────────────────
const structs = Array.from({length:30}, () => ({
  angle : Math.random()*Math.PI*2,
  radius: 148 + Math.random()*55,
  speed : (Math.random()-.5)*.005,
  size  : Math.random()*2.6+0.5,
  alpha : Math.random()*.5+.2,
  type  : Math.floor(Math.random()*3),
  phase : Math.random()*Math.PI*2
}));

function drawStructure(t, cx, cy) {
  ctx.save();
  ctx.translate(cx, cy);

  // Outer dashed orbit
  ctx.save();
  ctx.rotate(t*.18); ctx.scale(1,.36);
  ctx.strokeStyle='rgba(201,168,76,.12)'; ctx.lineWidth=1;
  ctx.setLineDash([4,10]);
  ctx.beginPath(); ctx.arc(0,0,158,0,Math.PI*2); ctx.stroke();
  ctx.setLineDash([]); ctx.restore();

  // Inner dashed orbit
  ctx.save();
  ctx.rotate(-t*.24); ctx.scale(1,.30);
  ctx.strokeStyle='rgba(201,168,76,.08)'; ctx.lineWidth=1;
  ctx.setLineDash([2,14]);
  ctx.beginPath(); ctx.arc(0,0,128,0,Math.PI*2); ctx.stroke();
  ctx.setLineDash([]); ctx.restore();

  // Orbiting particles
  structs.forEach(s => {
    s.angle += s.speed;
    const px = Math.cos(s.angle)*s.radius;
    const py = Math.sin(s.angle)*s.radius*.36;
    const pulse = .5+.5*Math.sin(t*1.3+s.phase);
    ctx.save();
    ctx.translate(px, py);
    ctx.globalAlpha = s.alpha*(.5+pulse*.5);
    ctx.strokeStyle = GOLDL; ctx.fillStyle = GOLDL; ctx.lineWidth=1;
    if (s.type===0) {
      ctx.beginPath(); ctx.arc(0,0,s.size,0,Math.PI*2); ctx.fill();
    } else if (s.type===1) {
      const r=s.size*2.5;
      ctx.beginPath(); ctx.moveTo(-r,0); ctx.lineTo(r,0); ctx.stroke();
      ctx.beginPath(); ctx.moveTo(0,-r); ctx.lineTo(0,r); ctx.stroke();
    } else {
      const r=s.size*2.2;
      ctx.beginPath(); ctx.moveTo(0,-r); ctx.lineTo(r,0); ctx.lineTo(0,r); ctx.lineTo(-r,0); ctx.closePath(); ctx.stroke();
    }
    ctx.restore();
  });

  // Cardinal tick marks
  [0,Math.PI/2,Math.PI,Math.PI*1.5].forEach((a,i)=>{
    const ang = a+t*.05;
    const r1=170, r2=182;
    const x1=Math.cos(ang)*r1, y1=Math.sin(ang)*r1*.36;
    const x2=Math.cos(ang)*r2, y2=Math.sin(ang)*r2*.36;
    ctx.strokeStyle=`rgba(201,168,76,${.3+.2*Math.sin(t+i)})`;
    ctx.lineWidth=1.5;
    ctx.beginPath(); ctx.moveTo(x1,y1); ctx.lineTo(x2,y2); ctx.stroke();
  });

  ctx.restore();
}

// ── SONY ALPHA CAMERA DRAWING ─────────────────────────────────
function drawCamera(t) {
  ctx.clearRect(0,0,420,420);
  const cx=210, cy=210;
  const floatY = Math.sin(t*.55)*11;
  const tiltX  = Math.sin(t*.38)*.06;
  const sc     = 1+Math.sin(t*.7)*.012;

  // Gold structure behind
  drawStructure(t, cx, cy+floatY);

  ctx.save();
  ctx.translate(cx, cy+floatY);
  ctx.scale(sc, sc);
  ctx.transform(1, tiltX, 0, 1, 0, 0);

  // ── SHADOW
  ctx.save();
  ctx.translate(5,100); ctx.scale(1,.24);
  const sh=ctx.createRadialGradient(0,0,8,0,0,92);
  sh.addColorStop(0,'rgba(0,0,0,.22)'); sh.addColorStop(1,'rgba(0,0,0,0)');
  ctx.fillStyle=sh; ctx.beginPath(); ctx.ellipse(0,0,92,72,0,0,Math.PI*2); ctx.fill();
  ctx.restore();

  // ── HAND GRIP (right)
  const gGrad=ctx.createLinearGradient(72,-54,110,54);
  gGrad.addColorStop(0,'#2c2c2c'); gGrad.addColorStop(1,'#181818');
  ctx.fillStyle=gGrad;
  ctx.beginPath();
  ctx.moveTo(72,-54); ctx.lineTo(108,-52);
  ctx.quadraticCurveTo(114,-48,114,2);
  ctx.quadraticCurveTo(113,50,103,54); ctx.lineTo(72,54); ctx.closePath();
  ctx.fill();
  // grip ridges
  for(let i=0;i<8;i++){
    ctx.strokeStyle='rgba(255,255,255,.04)'; ctx.lineWidth=1.5;
    ctx.beginPath(); ctx.moveTo(76,-44+i*13); ctx.lineTo(104,-44+i*13); ctx.stroke();
  }

  // ── MAIN BODY
  const bGrad=ctx.createLinearGradient(-104,-54,104,54);
  bGrad.addColorStop(0,'#3d3d3d'); bGrad.addColorStop(.35,'#2b2b2b');
  bGrad.addColorStop(.7,'#222'); bGrad.addColorStop(1,'#171717');
  ctx.fillStyle=bGrad;
  ctx.beginPath(); ctx.roundRect(-104,-54,208,108,11); ctx.fill();
  // top highlight
  const tHL=ctx.createLinearGradient(-104,-54,104,-54);
  tHL.addColorStop(0,'rgba(255,255,255,0)'); tHL.addColorStop(.5,'rgba(255,255,255,.07)'); tHL.addColorStop(1,'rgba(255,255,255,0)');
  ctx.fillStyle=tHL; ctx.fillRect(-104,-54,208,3);

  // ── GOLD ACCENT LINE (Sony signature)
  const acG=ctx.createLinearGradient(-104,0,104,0);
  acG.addColorStop(0,'rgba(201,168,76,0)'); acG.addColorStop(.15,GOLD); acG.addColorStop(.85,GOLD); acG.addColorStop(1,'rgba(201,168,76,0)');
  ctx.strokeStyle=acG; ctx.lineWidth=2;
  ctx.beginPath(); ctx.moveTo(-104,44); ctx.lineTo(104,44); ctx.stroke();

  // ── TOP HUMP
  const hGrad=ctx.createLinearGradient(-36,-80,36,-54);
  hGrad.addColorStop(0,'#363636'); hGrad.addColorStop(1,'#272727');
  ctx.fillStyle=hGrad;
  ctx.beginPath(); ctx.roundRect(-36,-78,72,26,5); ctx.fill();
  ctx.strokeStyle='rgba(201,168,76,.22)'; ctx.lineWidth=.8;
  ctx.beginPath(); ctx.roundRect(-36,-78,72,26,5); ctx.stroke();

  // EVF window
  ctx.fillStyle='#0c0c0c';
  ctx.beginPath(); ctx.roundRect(-29,-74,58,17,3); ctx.fill();
  ctx.strokeStyle='rgba(201,168,76,.45)'; ctx.lineWidth=.8;
  ctx.beginPath(); ctx.roundRect(-29,-74,58,17,3); ctx.stroke();
  const evf=ctx.createLinearGradient(-29,-74,29,-57);
  evf.addColorStop(0,'rgba(90,150,255,.14)'); evf.addColorStop(1,'rgba(0,0,80,.22)');
  ctx.fillStyle=evf; ctx.beginPath(); ctx.roundRect(-29,-74,58,17,3); ctx.fill();

  // ── HOT SHOE
  ctx.fillStyle=GOLD; ctx.fillRect(-17,-80,34,5);
  ctx.fillStyle='rgba(201,168,76,.4)';
  [-13,-4,4,13].forEach(x=>ctx.fillRect(x,-80,2.5,5));

  // ── MODE DIAL
  ctx.save(); ctx.translate(70,-62);
  const dG=ctx.createRadialGradient(0,0,2,0,0,19);
  dG.addColorStop(0,'#4c4c4c'); dG.addColorStop(1,'#1e1e1e');
  ctx.fillStyle=dG; ctx.beginPath(); ctx.arc(0,0,19,0,Math.PI*2); ctx.fill();
  ctx.strokeStyle=GOLD; ctx.lineWidth=1.3; ctx.beginPath(); ctx.arc(0,0,19,0,Math.PI*2); ctx.stroke();
  for(let i=0;i<12;i++){
    const a=(i/12)*Math.PI*2+t*.28;
    ctx.strokeStyle=i%3===0?GOLD:'rgba(201,168,76,.32)'; ctx.lineWidth=i%3===0?1.6:.8;
    ctx.beginPath(); ctx.moveTo(Math.cos(a)*12,Math.sin(a)*12); ctx.lineTo(Math.cos(a)*17.5,Math.sin(a)*17.5); ctx.stroke();
  }
  ctx.fillStyle=GOLD; ctx.beginPath(); ctx.arc(0,0,3.5,0,Math.PI*2); ctx.fill();
  ctx.restore();

  // ── SHUTTER BUTTON
  ctx.save(); ctx.translate(84,-48);
  const sbG=ctx.createRadialGradient(-2,-2,1,0,0,11);
  sbG.addColorStop(0,GOLDL); sbG.addColorStop(1,GOLD);
  ctx.fillStyle=sbG; ctx.beginPath(); ctx.arc(0,0,11,0,Math.PI*2); ctx.fill();
  ctx.strokeStyle='rgba(201,168,76,.6)'; ctx.lineWidth=1.5; ctx.beginPath(); ctx.arc(0,0,11,0,Math.PI*2); ctx.stroke();
  ctx.fillStyle='rgba(255,255,255,.24)'; ctx.beginPath(); ctx.ellipse(-3,-3,5.5,3.2,-Math.PI/4,0,Math.PI*2); ctx.fill();
  ctx.restore();

  // ── FRONT DIAL
  ctx.save(); ctx.translate(84,32);
  ctx.fillStyle='#2a2a2a'; ctx.beginPath(); ctx.roundRect(-13,-9,26,17,4); ctx.fill();
  ctx.strokeStyle='rgba(201,168,76,.28)'; ctx.lineWidth=.8; ctx.beginPath(); ctx.roundRect(-13,-9,26,17,4); ctx.stroke();
  ctx.restore();

  // ── STATUS LCD
  ctx.fillStyle='#0a1a0a'; ctx.beginPath(); ctx.roundRect(40,-70,42,17,3); ctx.fill();
  ctx.strokeStyle='rgba(201,168,76,.18)'; ctx.lineWidth=.8; ctx.beginPath(); ctx.roundRect(40,-70,42,17,3); ctx.stroke();
  ctx.fillStyle='rgba(80,220,80,.75)'; ctx.font='7px monospace'; ctx.textAlign='center';
  ctx.fillText('1/500',61,-58);

  // ── SONY LOGO
  ctx.fillStyle='rgba(255,255,255,.58)'; ctx.font='bold 10px Arial'; ctx.textAlign='center';
  ctx.fillText('SONY',66,-32);
  ctx.fillStyle=GOLD; ctx.font='500 8px Montserrat,Arial';
  ctx.fillText('α7 IV',66,-20);

  // ── E-MOUNT RING
  const mG=ctx.createRadialGradient(-6,-6,5,0,0,76);
  mG.addColorStop(0,'#3e3e3e'); mG.addColorStop(.5,'#1c1c1c'); mG.addColorStop(1,'#101010');
  ctx.fillStyle=mG; ctx.beginPath(); ctx.arc(-8,0,74,0,Math.PI*2); ctx.fill();
  ctx.strokeStyle=GOLD; ctx.lineWidth=3.8; ctx.beginPath(); ctx.arc(-8,0,74,0,Math.PI*2); ctx.stroke();
  ctx.strokeStyle='rgba(201,168,76,.5)'; ctx.lineWidth=1.1; ctx.beginPath(); ctx.arc(-8,0,67,0,Math.PI*2); ctx.stroke();
  // red dot
  ctx.fillStyle='#cc2200';
  ctx.beginPath(); ctx.arc(-8-72*Math.cos(.25),-72*Math.sin(.25),3.8,0,Math.PI*2); ctx.fill();

  // AF lamp
  ctx.fillStyle='rgba(255,130,0,.65)'; ctx.beginPath(); ctx.arc(-98,28,4.5,0,Math.PI*2); ctx.fill();

  // ── LENS BARREL
  ctx.fillStyle='#131313'; ctx.beginPath(); ctx.ellipse(-4,2,62,62,0,0,Math.PI*2); ctx.fill();
  const barG=ctx.createRadialGradient(-20,-15,8,-8,0,62);
  barG.addColorStop(0,'#3c3c3c'); barG.addColorStop(.5,'#212121'); barG.addColorStop(1,'#0d0d0d');
  ctx.fillStyle=barG; ctx.beginPath(); ctx.arc(-8,0,62,0,Math.PI*2); ctx.fill();

  // Lens rings
  [[54,'rgba(201,168,76,.72)'],[45,'rgba(201,168,76,.44)'],[35,'rgba(201,168,76,.24)'],[27,'rgba(201,168,76,.14)']].forEach(([r,c],i)=>{
    ctx.strokeStyle=c; ctx.lineWidth=i===0?1.8:1;
    ctx.beginPath(); ctx.arc(-8,0,r,0,Math.PI*2); ctx.stroke();
  });

  // Gold aperture ring on lens
  ctx.strokeStyle=GOLD; ctx.lineWidth=2.5;
  ctx.beginPath(); ctx.arc(-8,0,54,Math.PI*.15,Math.PI*.55); ctx.stroke();
  ctx.beginPath(); ctx.arc(-8,0,54,Math.PI*1.15,Math.PI*1.55); ctx.stroke();

  // Focus ring ribs
  for(let i=0;i<28;i++){
    const a=(i/28)*Math.PI*2+t*.1;
    ctx.strokeStyle='rgba(255,255,255,.05)'; ctx.lineWidth=2.2;
    ctx.beginPath(); ctx.moveTo(-8+Math.cos(a)*46,Math.sin(a)*46); ctx.lineTo(-8+Math.cos(a)*54,Math.sin(a)*54); ctx.stroke();
  }

  // Lens glass
  const gl=ctx.createRadialGradient(-17,-17,2,-8,0,25);
  gl.addColorStop(0,'rgba(160,205,255,.32)'); gl.addColorStop(.4,'rgba(55,95,200,.18)'); gl.addColorStop(.8,'rgba(8,18,80,.46)'); gl.addColorStop(1,'rgba(0,0,28,.72)');
  ctx.fillStyle=gl; ctx.beginPath(); ctx.arc(-8,0,25,0,Math.PI*2); ctx.fill();
  // aperture blades
  ctx.strokeStyle='rgba(201,168,76,.13)'; ctx.lineWidth=1;
  for(let i=0;i<7;i++){
    const a=(i/7)*Math.PI*2+t*.09;
    ctx.beginPath(); ctx.moveTo(-8,0); ctx.lineTo(-8+Math.cos(a)*23,Math.sin(a)*23); ctx.stroke();
  }
  // specular highlight
  ctx.fillStyle='rgba(255,255,255,.24)'; ctx.beginPath(); ctx.ellipse(-15,-11,9.5,5.5,-Math.PI/4,0,Math.PI*2); ctx.fill();
  ctx.fillStyle='rgba(255,255,255,.09)'; ctx.beginPath(); ctx.ellipse(-5,-16,4.5,2.5,-Math.PI/4,0,Math.PI*2); ctx.fill();

  // ── FOCUS BRACKET
  const fpA=.28+.28*Math.sin(t*3);
  ctx.strokeStyle=`rgba(201,168,76,${fpA})`; ctx.lineWidth=.9;
  const bs=20, bx=-8;
  [[-1,-1],[1,-1],[-1,1],[1,1]].forEach(([sx,sy])=>{
    ctx.beginPath(); ctx.moveTo(bx+sx*bs,sy*bs*.55); ctx.lineTo(bx+sx*bs,sy*bs); ctx.lineTo(bx+sx*bs-sx*9,sy*bs); ctx.stroke();
  });

  ctx.restore();

  // Ambient glow
  const glow=ctx.createRadialGradient(cx,cy+floatY,35,cx,cy+floatY,165);
  glow.addColorStop(0,'rgba(201,168,76,.06)'); glow.addColorStop(1,'rgba(201,168,76,0)');
  ctx.fillStyle=glow; ctx.beginPath(); ctx.ellipse(cx,cy+floatY,165,135,0,0,Math.PI*2); ctx.fill();
}

// ── ANIMATE ───────────────────────────────────────────────────
(function loop(ts){
  drawCamera(ts*.001);
  requestAnimationFrame(loop);
})(0);
</script>
</body>
</html>
