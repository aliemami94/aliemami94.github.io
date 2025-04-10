---
layout: frontpage
title: Ali Emami Kopaei
description: Ph.D. Physics, physics at the Jagiellonian University, Krakow, Poland.
---

<!-- Bootstrap + AOS + Icons -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
  body {
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to bottom, #001f3f, #003366);
    color: #fff;
    height: 100vh;
    overflow-x: hidden;
  }

  .navbar {
    background-color: #00122e;
  }

  .navbar a {
    color: #fff !important;
  }

  .navbar a:hover {
    color: #00d4ff !important;
  }

  .container {
    padding-top: 100px;
  }

  .section {
    background: rgba(255, 255, 255, 0.05);
    backdrop-filter: blur(6px);
    border-radius: 1rem;
    padding: 2rem;
    margin-bottom: 2rem;
    box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
  }

  .section-title {
    font-size: 1.6rem;
    border-bottom: 1px solid #ccc;
    margin-bottom: 1rem;
  }

  .nav-tabs .nav-link {
    color: #ccc;
    border-radius: 0.5rem 0.5rem 0 0;
    background-color: rgba(0,0,0,0.2);
  }

  .nav-tabs .nav-link.active {
    background-color: #004080;
    color: #fff;
  }

  .profile-img {
    max-width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.3);
    transition: transform 0.3s;
  }

  .profile-img:hover {
    transform: scale(1.05);
  }

  footer {
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
    background: #001a33;
    color: #aaa;
    margin-top: 4rem;
  }
</style>

<nav class="navbar navbar-expand-lg fixed-top shadow">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">Ali Emami Kopaei</a>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="#research">Research</a></li>
        <li class="nav-item"><a class="nav-link" href="#teaching">Teaching</a></li>
        <li class="nav-item"><a class="nav-link" href="{{ BASE_PATH }}/assets/cv_ali.pdf"><i class="bi bi-file-person"></i> CV</a></li>
        <li class="nav-item"><a class="nav-link" href="https://github.com/aliemami94"><i class="bi bi-github"></i></a></li>
        <li class="nav-item"><a class="nav-link" href="https://www.linkedin.com/in/ali-e-7b5b25120/"><i class="bi bi-linkedin"></i></a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">

  <div class="row align-items-center mb-5" data-aos="fade-up">
    <div class="col-md-8">
      <h2>About Me</h2>
      <p>I am currently a Ph.D. student in physics at the <strong>Jagiellonian University</strong>, Krakow, Poland, working with 
      <a href="https://chaos.if.uj.edu.pl/~sacha/" target="_blank" class="text-info">Prof. Krzysztof Sacha</a>. 
      My research focuses on <strong>Time Crystalline behavior</strong> and Quantum Systems.</p>
    </div>
    <div class="col-md-4 text-center">
      <img src="../assets/IMG_4313.png" alt="Ali Emami Kopaei" class="profile-img mt-3">
    </div>
  </div>

  <!-- Tabs for Research / Teaching -->
  <ul class="nav nav-tabs mb-4" id="myTab" role="tablist">
    <li class="nav-item" role="presentation">
      <button class="nav-link active" id="research-tab" data-bs-toggle="tab" data-bs-target="#research" type="button" role="tab">Research</button>
    </li>
    <li class="nav-item" role="presentation">
      <button class="nav-link" id="teaching-tab" data-bs-toggle="tab" data-bs-target="#teaching" type="button" role="tab">Teaching</button>
    </li>
  </ul>

  <div class="tab-content" id="myTabContent">

    <!-- Research Section -->
    <div class="tab-pane fade show active section" id="research" role="tabpanel" aria-labelledby="research-tab">
      <div class="section-title">Research Interests</div>
      <ul>
        <li>Time Crystals</li>
        <li>Condensed Matter Theory</li>
        <li>Quantum Many-Body Physics</li>
        <li>Quantum Statistical Physics</li>
        <li>Computational Physics</li>
        <li>Neural Networks & Machine Learning</li>
      </ul>

      <div class="section-title mt-4">Computational Expertise</div>
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

    <!-- Teaching Section -->
    <div class="tab-pane fade section" id="teaching" role="tabpanel" aria-labelledby="teaching-tab">
      <div class="section-title">Teaching & Mentorship</div>
      <p>I have supervised undergraduate and graduate-level students in physics and computational methods. Topics have included:</p>
      <ul>
        <li>Quantum Computing Fundamentals</li>
        <li>Simulating Time Crystals with Python</li>
        <li>Machine Learning for Physics</li>
        <li>Advanced Quantum Mechanics</li>
      </ul>
      <p>I'm also available for tutoring or collaborative teaching in areas such as computational physics and neural networks.</p>
    </div>
  </div>

  <div class="section" data-aos="fade-in">
    <div class="section-title">Contact</div>
    <p><i class="bi bi-envelope-fill"></i> ali.emami.app@gmail.com<br>
       <i class="bi bi-envelope-open-heart"></i> ali.emami.kopaei.@doctoral.uj.edu.pl</p>
  </div>

  <p class="text-center" data-aos="zoom-in">
    <a href="{{ BASE_PATH }}/assets/cv_ali.pdf" class="btn btn-outline-light btn-lg mt-3">
      <i class="bi bi-file-earmark-pdf"></i> Download CV
    </a>
  </p>
</div>

<footer>
  &copy; {{ site.time | date: '%Y' }} Ali Emami Kopaei. All rights reserved.
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init();</script>
