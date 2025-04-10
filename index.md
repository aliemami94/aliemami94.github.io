---
layout: frontpage
title: Ali Emami Kopaei
description: Ph.D. Physics, physics at the Jagiellonian University, Krakow, Poland.
keywords: Ali Emami Kopaei, A.Emami Kopaei, Ali Emami, A.Emami, Ali Emami Kopaei physics, A E Kopaei, A Emami Kopaei, a emami kopaei, ali emami kopaei, UJ ali emami
---

<!-- Bootstrap + Icons + AOS Animations -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

<style>
  body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to bottom, #fff0f0 0%, #ffe0e0 100%);
    color: #222;
    scroll-behavior: smooth;
  }
  .navbar {
    background-color: #880808;
  }
  .navbar a {
    color: white !important;
  }
  .navbar a:hover {
    color: #ffcc00 !important;
  }
  .profile-img {
    max-width: 100%;
    border-radius: 1rem;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    transition: transform 0.4s ease-in-out;
  }
  .profile-img:hover {
    transform: scale(1.05);
  }
  .section {
    background: linear-gradient(145deg, #ff9999, #ff6666);
    color: white;
    border-radius: 1rem;
    padding: 2rem;
    margin-bottom: 2rem;
    box-shadow: 0 6px 20px rgba(0,0,0,0.2);
  }
  .section-title {
    border-bottom: 2px solid #fff;
    margin-bottom: 1rem;
    padding-bottom: .5rem;
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
    0% { background-position-x: 0; }
    100% { background-position-x: 1000px; }
  }
</style>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg fixed-top shadow">
  <div class="container">
    <a class="navbar-brand text-white fw-bold" href="#">Ali Emami Kopaei</a>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="{{ BASE_PATH }}/assets/cv_ali.pdf"><i class="bi bi-file-earmark-person"></i> CV</a></li>
        <li class="nav-item"><a class="nav-link" href="https://github.com/aliemami94"><i class="bi bi-github"></i> GitHub</a></li>
        <li class="nav-item"><a class="nav-link" href="https://www.linkedin.com/in/ali-e-7b5b25120/"><i class="bi bi-linkedin"></i> LinkedIn</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Main Container -->
<div class="container mt-5 pt-5">

  <div class="row align-items-center mb-5" data-aos="fade-up">
    <div class="col-md-8">
      <h2 class="mb-3">About Me</h2>
      <p>I am currently a Ph.D. student in physics at the <strong>Jagiellonian University</strong>, Krakow, Poland, working with 
      <a href="https://chaos.if.uj.edu.pl/~sacha/" target="_blank">Prof. Krzysztof Sacha</a>. My research focuses on 
      <strong>Time Crystalline behavior</strong> and modern quantum systems.</p>
    </div>
    <div class="col-md-4 text-center">
      <img src="../assets/IMG_4313.png" alt="Ali Emami Kopaei" class="profile-img mt-3">
    </div>
  </div>

  <div class="wave"></div>

  <div class="section" data-aos="fade-right">
    <div class="section-title">Contact</div>
    <p><i class="bi bi-envelope-fill"></i> ali.emami.app@gmail.com<br>
       <i class="bi bi-envelope-open-heart"></i> ali.emami.kopaei.@doctoral.uj.edu.pl</p>
  </div>

  <div class="section" data-aos="fade-left">
    <div class="section-title">Research Interests</div>
    <ul>
      <li>Time Crystals</li>
      <li>Condensed Matter Theory</li>
      <li>Quantum Many-Body Physics</li>
      <li>Quantum Statistical Physics</li>
      <li>Computational Physics</li>
      <li>Neural Networks & Machine Learning</li>
    </ul>
  </div>

  <div class="section" data-aos="fade-up">
    <div class="section-title">Computational Expertise</div>
    <ol>
      <li>Artificial Neural Networks</li>
      <li>Deep Learning Phases of Matter</li>
      <li>Tensor Network Methods (MPS)</li>
      <li>Exact Diagonalization</li>
      <li>DMRG</li>
      <li>TEBD</li>
      <li>Quantum Monte Carlo</li>
      <li>Krylov Subspace Iteration</li>
    </ol>
  </div>

  <p class="text-center" data-aos="zoom-in">
    <a href="{{ BASE_PATH }}/assets/cv_ali.pdf" class="btn btn-outline-light btn-lg mt-3">
      <i class="bi bi-file-earmark-pdf"></i> Download CV
    </a>
  </p>

</div>

<!-- AOS Script -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init();</script>
