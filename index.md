---
layout: frontpage
title: Ali Emami Kopaei
description: Ph.D. Physics, physics at the Jagiellonian University, Krakow, Poland.
---

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">

<style>
  body {
    background-color: #0a0f2c;
    color: #ffffffd9;
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 0;
    overflow-x: hidden;
    min-height: 100vh;
  }

  .main-card {
    max-width: 850px;
    margin: 80px auto;
    background: rgba(10, 18, 48, 0.85);
    border-radius: 1.5rem;
    box-shadow: 0 0 60px rgba(0, 255, 255, 0.08);
    padding: 3rem;
    text-align: center;
    backdrop-filter: blur(10px);
  }

  h1 {
    font-size: 2.5rem;
    font-weight: 600;
    color: #00ccff;
  }

  .img-circle {
    border-radius: 50%;
    width: 180px;
    height: 180px;
    object-fit: cover;
    box-shadow: 0 0 25px rgba(0, 255, 255, 0.2);
    margin-bottom: 1rem;
  }

  .section-title {
    margin-top: 2rem;
    font-size: 1.4rem;
    color: #88e1f2;
    border-bottom: 1px solid rgba(255,255,255,0.2);
    padding-bottom: 0.5rem;
  }

  .contact-info {
    margin-top: 1.5rem;
    font-size: 0.95rem;
    color: #bbb;
  }

  .btn-custom {
    background-color: #00b4d8;
    border: none;
    padding: 0.6rem 1.2rem;
    font-size: 1rem;
    color: white;
    border-radius: 0.5rem;
    margin: 1rem;
    transition: background 0.3s;
  }

  .btn-custom:hover {
    background-color: #0097b2;
  }

  .social-icons a {
    margin: 0 0.5rem;
    color: #ffffffc2;
    font-size: 1.4rem;
    transition: color 0.3s;
  }

  .social-icons a:hover {
    color: #00f7ff;
  }
</style>

<div class="main-card">
  <img src="../assets/IMG_4313.png" alt="Ali Emami Kopaei" class="img-circle">
  <h1>Ali Emami Kopaei</h1>
  <p class="lead">Ph.D. Candidate in Physics<br>
    Jagiellonian University, Krakow, Poland</p>

  <div class="contact-info">
    <p><i class="bi bi-envelope-fill"></i> ali.emami.app@gmail.com<br>
       <i class="bi bi-envelope-fill"></i> ali.emami.kopaei.@doctoral.uj.edu.pl</p>
  </div>

  <div class="section-title">Research Interests</div>
  <p>Time Crystals, Quantum Many-Body Physics, Neural Networks in Physics, Tensor Networks, TEBD, DMRG</p>

  <div class="section-title">Computational Expertise</div>
  <p>Machine Learning, Tensor Network Simulations, Exact Diagonalization, Quantum Monte Carlo, Krylov Methods</p>

  <a href="{{ BASE_PATH }}/assets/cv_ali.pdf" class="btn btn-custom"><i class="bi bi-file-earmark-pdf-fill"></i> CV</a>

  <div class="social-icons mt-3">
    <a href="https://github.com/aliemami94"><i class="bi bi-github"></i></a>
    <a href="https://www.linkedin.com/in/ali-e-7b5b25120/"><i class="bi bi-linkedin"></i></a>
  </div>
</div>
