---
layout: frontpage
title: Ali Emami Kopaei
description: Ph.D. Physics, physics at the Jagiellonian University, Krakow, Poland.
keywords: Ali Emami Kopaei, A.Emami Kopaei, Ali Emami, A.Emami, Ali Emami Kopaei physics, A E Kopaei, A Emami Kopaei, a emami kopaei, ali emami kopaei, UJ ali emami
---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ali Emami Kopaei</title>

  <link rel="icon" type="image/png" href="{{ BASE_PATH }}/assets/favicon.png" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

  <style>
    :root {
      --bg-dark: #060913;
      --panel-bg: rgba(15, 23, 42, 0.75);
      --accent-cyan: #38bdf8;
      --accent-purple: #818cf8;
      --text-main: #f1f5f9;
      --text-muted: #cbd5e1;
    }

    body { font-family: 'Segoe UI', system-ui, -apple-system, sans-serif; background-color: var(--bg-dark); color: var(--text-main); scroll-behavior: smooth; overflow-x: hidden; position: relative; }
    #quantum-canvas { position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; z-index: -2; pointer-events: none; }
    .ambient-glow { position: fixed; top: -10%; left: -10%; width: 120%; height: 120%; background: radial-gradient(circle at 70% 20%, rgba(56, 189, 248, 0.05), transparent 40%), radial-gradient(circle at 20% 80%, rgba(129, 140, 248, 0.05), transparent 45%); z-index: -1; pointer-events: none; }
    .navbar { background: rgba(6, 9, 19, 0.85) !important; backdrop-filter: blur(12px); border-bottom: 1px solid rgba(255, 255, 255, 0.08); padding: 0.75rem 2rem; }
    .profile-img { max-width: 100%; height: auto; border-radius: 1.1rem; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5); transition: transform 0.4s ease; background: #0f172a; }
    .section { background: var(--panel-bg); backdrop-filter: blur(16px); border: 1px solid rgba(255, 255, 255, 0.06); border-radius: 1.25rem; padding: 2.5rem; margin-bottom: 2rem; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3); }
    .section-title { font-size: 1.5rem; font-weight: 700; text-transform: uppercase; color: var(--accent-cyan); border-bottom: 1px solid rgba(255, 255, 255, 0.1); margin-bottom: 1.5rem; padding-bottom: 0.75rem; display: flex; align-items: center; gap: 0.7rem; }
    a.academic-link { color: var(--accent-cyan); text-decoration: none; transition: all 0.3s ease; }
    a.academic-link:hover { color: var(--accent-purple); }
    .floating-box { background: rgba(15, 23, 42, 0.9) !important; backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.08); border-right: none; border-radius: 1rem 0 0 1rem; padding: 1.25rem !important; z-index: 1030; }
  </style>
</head>

<body>
  <canvas id="quantum-canvas"></canvas>
  <div class="ambient-glow"></div>

  <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
    <div class="container-fluid">
      <span class="navbar-brand fw-bold fs-5">AEK</span>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav gap-2">
          <li class="nav-item"><a class="nav-link" href="/assets/CV_Ali.E.Kopaei_2025.pdf"><i class="bi bi-file-earmark-person"></i> CV</a></li>
          <li class="nav-item"><a class="nav-link" href="https://github.com/aliemami94"><i class="bi bi-github"></i> GitHub</a></li>
          <li class="nav-item"><a class="btn btn-outline-info btn-sm" href="https://aliemami94.github.io/pages/research.html">🧪 Research</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <main class="container py-5">
    <div class="section" data-aos="fade-up">
      <div class="row align-items-center g-4">
        <div class="col-md-8">
          <h1 class="display-5 fw-bold mb-2">Ali Emami Kopaei</h1>
          <p class="text-muted fs-5">Postdoctoral Researcher in Computational & Condensed Matter Physics</p>
          <p>I am a Postdoc at the University of Warsaw, working with Prof. Krzysztof Wohlfeld. I focus on engineered quantum dynamics, time crystals, and many-body systems using machine learning and tensor networks.</p>
        </div>
        <div class="col-md-4 text-center"><img src="../assets/IMG_4313.png" alt="Ali Emami Kopaei" class="profile-img" /></div>
      </div>
    </div>

    <div class="section" data-aos="fade-up">
      <div class="section-title"><i class="bi bi-cpu"></i> Selected Publications</div>
      <div class="d-flex flex-column gap-3">
        <div class="p-3 rounded border-1 border-dashed" style="background: rgba(255,255,255,0.02);">
          <h6 class="mb-1"><a href="https://arxiv.org/abs/2409.07885" class="academic-link">Photonic time crystals with periodic refractive index changes</a></h6>
          <div class="fs-7 text-info">arXiv:2409.07885v1 (Submitted to Phys. Rev. Lett.)</div>
        </div>
        <div class="p-3 rounded border-1 border-dashed" style="background: rgba(255,255,255,0.02);">
          <h6 class="mb-1"><a href="#" class="academic-link">Anderson localization in a photonic time crystal</a></h6>
          <div class="fs-7 text-info">Phys. Rev. B</div>
        </div>
      </div>
      <div class="text-end mt-3"><a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&hl=en" class="text-info text-decoration-none">Full Publication List <i class="bi bi-arrow-right"></i></a></div>
    </div>
  </main>

  <div class="floating-box position-fixed top-50 end-0 translate-middle-y d-none d-md-flex flex-column gap-2">
    <a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&hl=en" class="text-warning">Google Scholar</a>
    <a href="https://www.researchgate.net/profile/Ali-Emami-Kopaei-2" class="text-info">ResearchGate</a>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 800, once: true });
    const canvas = document.getElementById('quantum-canvas');
    const ctx = canvas.getContext('2d');
    let particles = [];
    function resizeCanvas() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
    window.addEventListener('resize', resizeCanvas); resizeCanvas();
    class Particle { constructor() { this.x = Math.random()*canvas.width; this.y = Math.random()*canvas.height; this.vx = (Math.random()-0.5)*0.4; this.vy = (Math.random()-0.5)*0.4; } update() { this.x+=this.vx; this.y+=this.vy; if(this.x<0||this.x>canvas.width||this.y<0||this.y>canvas.height) { this.x=Math.random()*canvas.width; this.y=Math.random()*canvas.height; } } draw() { ctx.beginPath(); ctx.arc(this.x, this.y, 1.5, 0, Math.PI*2); ctx.fillStyle='rgba(56, 189, 248, 0.4)'; ctx.fill(); } }
    for(let i=0; i<65; i++) particles.push(new Particle());
    function animate() { ctx.clearRect(0, 0, canvas.width, canvas.height); particles.forEach(p => { p.update(); p.draw(); }); requestAnimationFrame(animate); }
    animate();
  </script>
</body>
</html>
