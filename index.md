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

    body {
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      background-color: var(--bg-dark);
      color: var(--text-main);
      scroll-behavior: smooth;
      overflow-x: hidden;
      position: relative;
    }

    /* Interactive Quantum Canvas Background */
    #quantum-canvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      z-index: -2;
      pointer-events: none;
    }

    /* Ambient Glow Overlay */
    .ambient-glow {
      position: fixed;
      top: -10%;
      left: -10%;
      width: 120%;
      height: 120%;
      background: radial-gradient(circle at 70% 20%, rgba(56, 189, 248, 0.05), transparent 40%),
                  radial-gradient(circle at 20% 80%, rgba(129, 140, 248, 0.05), transparent 45%);
      z-index: -1;
      pointer-events: none;
    }

    /* Professional Glassmorphic Navbar */
    .navbar {
      background: rgba(6, 9, 19, 0.85) !important;
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      padding: 0.75rem 2rem;
    }

    .navbar .nav-link {
      color: var(--text-muted) !important;
      font-weight: 500;
      transition: color 0.3s ease;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .navbar .nav-link:hover {
      color: var(--accent-cyan) !important;
    }

    /* Profile Image Styling */
    .profile-img-container {
      position: relative;
      display: inline-block;
    }

    .profile-img-container::before {
      content: '';
      position: absolute;
      inset: -4px;
      border-radius: 1.25rem;
      background: linear-gradient(45deg, var(--accent-cyan), var(--accent-purple));
      z-index: -1;
      opacity: 0.4;
      transition: opacity 0.4s ease;
    }

    .profile-img-container:hover::before {
      opacity: 0.8;
    }

    .profile-img {
      max-width: 100%;
      height: auto;
      border-radius: 1.1rem;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      transition: transform 0.4s ease;
      background: #0f172a;
    }

    .profile-img:hover {
      transform: translateY(-4px);
    }

    /* Content Cards */
    .section {
      background: var(--panel-bg);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.06);
      border-radius: 1.25rem;
      padding: 2.5rem;
      margin-bottom: 2rem;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
      transition: border-color 0.3s ease;
    }

    .section:hover {
      border-color: rgba(56, 189, 248, 0.2);
    }

    .section-title {
      font-size: 1.5rem;
      font-weight: 700;
      letter-spacing: 0.05em;
      text-transform: uppercase;
      color: var(--accent-cyan);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      margin-bottom: 1.5rem;
      padding-bottom: 0.75rem;
      display: flex;
      align-items: center;
      gap: 0.7rem;
    }

    /* Modern Typography Accents */
    a.academic-link {
      color: var(--accent-cyan);
      text-decoration: none;
      border-bottom: 1px dashed transparent;
      transition: all 0.3s ease;
    }

    a.academic-link:hover {
      color: var(--accent-purple);
      border-bottom-color: var(--accent-purple);
    }

    /* Custom Lists styling */
    .custom-list {
      list-style: none;
      padding-left: 0;
    }

    .custom-list li {
      position: relative;
      padding-left: 1.75rem;
      margin-bottom: 0.75rem;
      color: var(--text-muted);
    }

    .custom-list li::before {
      content: "•";
      position: absolute;
      left: 0.5rem;
      color: var(--accent-cyan);
      font-weight: bold;
      font-size: 1.2rem;
      top: -2px;
    }

    /* Numbered list custom styling */
    .custom-number-list {
      counter-reset: section;
      list-style: none;
      padding-left: 0;
    }

    .custom-number-list li {
      position: relative;
      padding-left: 2.25rem;
      margin-bottom: 0.85rem;
      color: var(--text-muted);
    }

    .custom-number-list li::before {
      counter-increment: section;
      content: counter(section);
      position: absolute;
      left: 0;
      top: 2px;
      background: rgba(129, 140, 248, 0.15);
      color: var(--accent-purple);
      font-size: 0.8rem;
      font-weight: 700;
      width: 1.5rem;
      height: 1.5rem;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Refined Floating Dock */
    .floating-box {
      background: rgba(15, 23, 42, 0.9) !important;
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-right: none;
      border-radius: 1rem 0 0 1rem;
      padding: 1.25rem !important;
      box-shadow: -5px 5px 25px rgba(0,0,0,0.5);
      z-index: 1030;
    }

    .floating-box h6 {
      font-weight: 700;
      font-size: 0.85rem;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      color: var(--text-muted);
    }

    .floating-box a {
      transition: transform 0.2s ease, color 0.2s ease;
      font-size: 0.9rem;
      text-decoration: none;
      margin-bottom: 0.5rem;
    }

    .floating-box a:hover {
      transform: translateX(-3px);
      color: var(--accent-cyan) !important;
    }

    /* Buttons */
    .btn-custom-outline {
      border: 1px solid rgba(255,255,255,0.2);
      color: var(--text-main);
      background: rgba(255,255,255,0.03);
      backdrop-filter: blur(8px);
      transition: all 0.3s ease;
    }

    .btn-custom-outline:hover {
      background: white;
      color: #060913;
      box-shadow: 0 0 15px rgba(255,255,255,0.3);
    }

    .navbar .btn-nav {
      font-size: 0.85rem;
      font-weight: 600;
      border-radius: 0.5rem;
      padding: 0.4rem 0.8rem;
    }
  </style>
</head>

<body>

  <canvas id="quantum-canvas"></canvas>
  <div class="ambient-glow"></div>

  <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
    <div class="container-fluid">
      <span class="navbar-brand fw-bold fs-5 tracking-wide text-white">AEK</span>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav align-items-lg-center gap-2">
          <li class="nav-item">
            <a class="nav-link" href="/assets/CV_Ali.E.Kopaei_2025.pdf">
              <i class="bi bi-file-earmark-person"></i> CV
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://github.com/aliemami94">
              <i class="bi bi-github"></i> GitHub
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://www.linkedin.com/in/ali-emami-kopaei-7b5b25120/">
              <i class="bi bi-linkedin"></i> LinkedIn
            </a>
          </li>
          <li class="nav-item ms-lg-2">
            <a class="btn btn-outline-info btn-nav btn-sm text-info" href="https://aliemami94.github.io/pages/research.html" target="_blank">
              🧪 Research
            </a>
          </li>
          <li class="nav-item">
            <a class="btn btn-outline-warning btn-nav btn-sm text-warning" href="https://aliemami94.github.io/pages/teaching.html" target="_blank">
              📘 Teaching
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <main class="container py-5">
    
    <div class="section" data-aos="fade-up">
      <div class="row align-items-center g-4">
        <div class="col-md-8 order-2 order-md-1">
          <h1 class="display-5 fw-bold mb-2">Ali Emami Kopaei</h1>
          <p class="text-muted mb-4 fs-5">Postdoctoral Researcher in Computational & Condensed Matter Physics</p>
          <p class="fs-6 leading-relaxed">
            I am currently a Postdoc in the field of physics, pursuing my research at Warsaw University, Poland, under the guidance of 
            <a href="https://www.fuw.edu.pl/~kwohlfeld/" target="_blank" class="academic-link">Prof. Krzysztof Wohlfeld</a>.
            My primary area of research revolves around the fascinating concepts of <strong>condensed matter theory</strong> and engineered quantum dynamics.
          </p>
          <p class="fs-6 mb-0">
            You can access the comprehensive record of my publications on 
            <a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&amp;hl=en" target="_blank" class="academic-link fw-semibold">
              <i class="bi bi-google"></i> Google Scholar
            </a>.
          </p>
        </div>
        <div class="col-md-4 order-1 order-md-2 text-center">
          <div class="profile-img-container">
            <img src="../assets/IMG_4313.png" alt="Ali Emami Kopaei" class="profile-img" />
          </div>
        </div>
      </div>
    </div>

    <div class="section" data-aos="fade-up">
      <div class="section-title">
        <i class="bi bi-cpu"></i> Research Focus
      </div>
      <p class="fs-6 leading-relaxed mb-4 text-secondary" style="color: var(--text-muted) !important;">
        My research focuses on engineered quantum dynamics, condensed matter theory, and quantum many-body physics. 
        I specialize in studying the stability and emergence of novel phases—such as discrete and photonic 
        <strong>time crystals</strong>—using advanced numerical techniques, tensor networks, and machine learning models. 
        My work involves active collaborations with researchers across global institutions, including the Max Planck Institute, NASA, and the University of Leeds.
      </p>

      <div class="section-title mt-5 fs-6" style="border-bottom: 1px dashed rgba(255,255,255,0.1); padding-bottom: 0.5rem; color: var(--text-main);">
        <i class="bi bi-journal-text text-info"></i> Latest from Google Scholar
      </div>
      
      <div id="scholar-publications-loading" class="text-center py-4">
        <div class="spinner-border spinner-border-sm text-info" role="status"></div>
        <span class="ms-2 text-muted fs-7">Fetching latest publications...</span>
      </div>

      <div id="scholar-publications-list" class="d-flex flex-column gap-3 mt-3">
        </div>
      
      <div class="text-end mt-3">
        <a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&hl=en" target="_blank" class="fs-7 text-info text-decoration-none">
          See all papers on Google Scholar <i class="bi bi-arrow-right"></i>
        </a>
      </div>
    </div>

    <div class="row g-4">
      <div class="col-md-6" data-aos="fade-right">
        <div class="section h-100">
          <div class="section-title"><i class="bi bi-bookmark-star"></i> Research Interests</div>
          <ul class="custom-list">
            <li>Time Crystals</li>
            <li>Condensed Matter Theory</li>
            <li>Quantum Many-Body Physics</li>
            <li>Quantum Statistical Physics</li>
            <li>Computational Physics</li>
            <li>Neural Networks & Machine Learning</li>
          </ul>
        </div>
      </div>

      <div class="col-md-6" data-aos="fade-left">
        <div class="section h-100">
          <div class="section-title"><i class="bi bi-terminal"></i> Computational Expertise</div>
          <ol class="custom-number-list">
            <li>Artificial Neural Networks & Deep Learning</li>
            <li>Tensor Network Methods (MPS, DMRG, TEBD)</li>
            <li>Exact Diagonalization</li>
            <li>Quantum Monte Carlo</li>
            <li>Krylov Subspace Iteration</li>
          </ol>
        </div>
      </div>
    </div>

    <div class="section mt-4" data-aos="fade-up">
      <div class="section-title"><i class="bi bi-envelope"></i> Contact & Communication</div>
      <div class="row">
        <div class="col-sm-6 mb-2 mb-sm-0">
          <div class="d-flex align-items-center gap-3">
            <i class="bi bi-envelope-fill text-info fs-4"></i>
            <div>
              <small class="text-muted d-block">Primary Email</small>
              <a href="mailto:ali.emami.app@gmail.com" class="text-white text-decoration-none">ali.emami.app@gmail.com</a>
            </div>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="d-flex align-items-center gap-3">
            <i class="bi bi-building text-warning fs-4"></i>
            <div>
              <small class="text-muted d-block">Academic Correspondence</small>
              <a href="mailto:ali.emami.kopaei.@doctoral.uj.edu.pl" class="text-white text-decoration-none fs-7">ali.emami.kopaei.@doctoral.uj.edu.pl</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="text-center mt-5" data-aos="zoom-in">
      <a href="/assets/CV_Ali.E.Kopaei_2025.pdf" class="btn btn-custom-outline btn-lg px-4 py-2 fs-6">
        <i class="bi bi-file-earmark-pdf me-2"></i> Download Full CV
      </a>
    </div>

  </main>

  <div class="floating-box position-fixed top-50 end-0 translate-middle-y d-none d-md-flex flex-column gap-2">
    <h6>Quick Links</h6>
    <a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&amp;hl=en" target="_blank" class="text-warning"><i class="bi bi-google me-1"></i> Scholar</a>
    <a href="https://www.researchgate.net/profile/Ali-Emami-Kopaei-2" target="_blank" class="text-info"><i class="bi bi-journal-text me-1"></i> ResearchGate</a>
    <a href="https://aliemami94.github.io/pages/research.html" target="_blank" class="text-warning">🧪 Research</a>
    <a href="https://aliemami94.github.io/pages/teaching.html" target="_blank" class="text-info">📘 Teaching</a>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 800, once: true });

    // --- AUTOMATIC GOOGLE SCHOLAR UPDATER ENGINE ---
    document.addEventListener("DOMContentLoaded", function() {
      const scholarId = "ooL_O7sAAAAJ";
      const targetUrl = `https://scholar.google.com/citations?user=${scholarId}&hl=en&pagesize=5`;
      const proxyUrl = `https://api.allorigins.win/get?url=${encodeURIComponent(targetUrl)}`;

      const listContainer = document.getElementById("scholar-publications-list");
      const loader = document.getElementById("scholar-publications-loading");

      fetch(proxyUrl)
        .then(response => {
          if (!response.ok) throw new Error("Proxy connection failed.");
          return response.json();
        })
        .then(data => {
          const parser = new DOMParser();
          const doc = parser.parseFromString(data.contents, "text/html");
          const rows = doc.querySelectorAll(".gsc_a_tr");

          if (rows.length === 0) {
            throw new Error("No publication rows parsed.");
          }

          loader.style.display = "none";

          rows.forEach((row, index) => {
            if (index >= 5) return; // Cap top 5 items

            const titleElement = row.querySelector(".gsc_a_at");
            const title = titleElement ? titleElement.textContent : "Untitled Publication";
            const relativeLink = titleElement ? titleElement.getAttribute("href") : "";
            const absoluteLink = relativeLink ? `https://scholar.google.com${relativeLink}` : `https://scholar.google.com/citations?user=${scholarId}`;
            
            const details = row.querySelectorAll(".gs_gray");
            const authors = details[0] ? details[0].textContent : "";
            const venue = details[1] ? details[1].textContent : "";

            const paperCard = document.createElement("div");
            paperCard.className = "p-3 rounded border-1 border-dashed";
            paperCard.style.background = "rgba(255,255,255,0.02)";
            paperCard.style.borderColor = "rgba(255,255,255,0.05)";
            
            paperCard.innerHTML = `
              <h6 class="mb-1 fs-6">
                <a href="${absoluteLink}" target="_blank" class="academic-link fw-semibold">${title}</a>
              </h6>
              <div class="fs-7 text-white-50 opacity-75">${authors}</div>
              <div class="fs-7 text-info opacity-70 mt-1"><i class="bi bi-journal-bookmark me-1"></i> ${venue}</div>
            `;
            listContainer.appendChild(paperCard);
          });
        })
        .catch(err => {
          console.error("Scholar update error: ", err);
          loader.innerHTML = `
            <span class="text-muted fs-7">
              <i class="bi bi-exclamation-circle text-warning me-1"></i> 
              Unable to load live feed directly. Please view updates on 
              <a href="https://scholar.google.com/citations?user=${scholarId}&hl=en" target="_blank" class="text-info">Google Scholar</a>.
            </span>`;
        });
    });

    // --- QUANTUM PARTICLE LATTICE SIMULATOR (Canvas Background) ---
    const canvas = document.getElementById('quantum-canvas');
    const ctx = canvas.getContext('2d');

    let particles = [];
    const maxParticles = 65; 
    let mouse = { x: null, y: null, radius: 150 };

    window.addEventListener('mousemove', (e) => {
      mouse.x = e.clientX;
      mouse.y = e.clientY;
    });

    window.addEventListener('mouseout', () => {
      mouse.x = null;
      mouse.y = null;
    });

    function resizeCanvas() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }
    window.addEventListener('resize', resizeCanvas);
    resizeCanvas();

    class Particle {
      constructor() { this.reset(); }
      reset() {
        this.x = Math.random() * canvas.width;
        this.y = Math.random() * canvas.height;
        this.vx = (Math.random() - 0.5) * 0.4;
        this.vy = (Math.random() - 0.5) * 0.4;
        this.radius = Math.random() * 1.5 + 1;
      }
      update() {
        this.x += this.vx;
        this.y += this.vy;
        if (this.x < 0 || this.x > canvas.width || this.y < 0 || this.y > canvas.height) this.reset();
        if (mouse.x !== null && mouse.y !== null) {
          let dx = this.x - mouse.x;
          let dy = this.y - mouse.y;
          let dist = Math.sqrt(dx * dx + dy * dy);
          if (dist < mouse.radius) {
            let force = (mouse.radius - dist) / mouse.radius;
            this.x += (dx / dist) * force * 2;
            this.y += (dy / dist) * force * 2;
          }
        }
      }
      draw() {
        ctx.beginPath();
        ctx.arc(this.x, this.y, this.radius, 0, Math.PI * 2);
        ctx.fillStyle = 'rgba(56, 189, 248, 0.4)';
        ctx.fill();
      }
    }

    function initParticles() {
      for (let i = 0; i < maxParticles; i++) particles.push(new Particle());
    }

    function drawLines() {
      for (let i = 0; i < particles.length; i++) {
        for (let j = i + 1; j < particles.length; j++) {
          let dx = particles[i].x - particles[j].x;
          let dy = particles[i].y - particles[j].y;
          let dist = Math.sqrt(dx * dx + dy * dy);
          if (dist < 120) {
            let alpha = (120 - dist) / 120 * 0.12;
            ctx.beginPath();
            ctx.moveTo(particles[i].x, particles[i].y);
            ctx.lineTo(particles[j].x, particles[j].y);
            ctx.strokeStyle = `rgba(129, 140, 248, ${alpha})`;
            ctx.lineWidth = 0.8;
            ctx.stroke();
          }
        }
      }
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      particles.forEach(p => { p.update(); p.draw(); });
      drawLines();
      requestAnimationFrame(animate);
    }

    initParticles();
    animate();
  </script>
</body>
</html>
