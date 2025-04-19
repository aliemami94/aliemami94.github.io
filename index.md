---
layout: frontpage
title: Ali Emami Kopaei
description: Ph.D. Physics, physics at the Jagiellonian University, Krakow, Poland.
keywords: Ali Emami Kopaei, A.Emami Kopaei, Ali Emami, A.Emami, Ali Emami Kopaei physics, A E Kopaei, A Emami Kopaei, a emami kopaei, ali emami kopaei, UJ ali emami
---

<!-- Favicon -->
<link rel="icon" type="image/png" href="{{ BASE_PATH }}/assets/favicon.png" />

<!-- Bootstrap + Icons + AOS Animations -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

<style>
  body {
    font-family: 'Segoe UI', sans-serif;
    background: url('/assets/Abstract-Time-Crystal-Concept.webp') no-repeat center center fixed;
    background-size: cover;
    color: #ffffff;
    scroll-behavior: smooth;
    position: relative;
    z-index: 1;
  }

  body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0.2, 0.2);
    z-index: -1;
  }

  .navbar {
    background-color: rgba(136, 8, 8, 0.85);
  }

  .navbar a {
    color: #000080 !important;
  }

  .navbar a:hover {
    color: #ffcc00 !important;
  }

  .profile-img {
    max-width: 100%;
    border-radius: 1rem;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
    transition: transform 0.4s ease-in-out;
  }

  .profile-img:hover {
    transform: scale(1.05);
  }

  .section {
    background: rgba(0, 0, 0, 0.75);
    color: white;
    border-radius: 1rem;
    padding: 2rem;
    margin-bottom: 2rem;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.5);
  }

  .section-title {
    border-bottom: 2px solid #fff;
    margin-bottom: 1rem;
    padding-bottom: 0.5rem;
    font-size: 1.5rem;
    font-weight: bold;
  }

  .wave {
    position: relative;
    width: 100%;
    height: 100px;
    background: url('https://raw.githubusercontent.com/aliemami94/aliemami94.github.io/main/assets/wave-red.svg') repeat-x;
    animation: wave 10s linear infinite;
    transform: rotate(180deg);
    margin-bottom: -3rem;
  }

  @keyframes wave {
    0% {
      background-position-x: 0;
    }
    100% {
      background-position-x: 1000px;
    }
  }

  .floating-box {
    position: fixed;
    top: 100px;
    right: 0;
    background-color: rgba(0, 0, 0, 0.85);
    padding: 1rem;
    border-radius: 1rem 0 0 1rem;
    z-index: 999;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
  }

  .floating-box .box-link {
    color: #ffcc00;
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
  }

  .floating-box h5 {
    border-bottom: 1px solid #fff;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
  }
</style>

<ul class="navbar-nav">
  <li class="nav-item">
    <a class="nav-link" href="{{ BASE_PATH }}/assets/cv_ali.pdf">
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
  <li class="nav-item">
    <a class="btn btn-warning btn-sm ms-2" href="https://aliemami94.github.io/pages/research.html" target="_blank">
      🧪 Research
    </a>
  </li>
  <li class="nav-item">
    <a class="btn btn-info btn-sm ms-2 text-white" href="https://aliemami94.github.io/pages/teaching.html" target="_blank">
      📘 Teaching
    </a>
  </li>
</ul>

<!-- Your existing body content remains untouched below this point -->

<!-- AOS Script -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init();</script>

<!-- Floating Side Box -->
<div class="floating-box">
  <h5 class="text-white">Quick Links</h5>
  <a href="https://aliemami94.github.io/pages/research.html" target="_blank" class="box-link">🧪 Research</a><br>
  <a href="https://aliemami94.github.io/pages/teaching.html" target="_blank" class="box-link">📘 Teaching</a>
</div>
