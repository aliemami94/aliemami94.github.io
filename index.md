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
    background: url('/assets/Abstract-Time-Crystal-Concept.webp') no-repeat center center fixed;
    background-size: cover;
    color: #ffffff;
    scroll-behavior: smooth;
    position: relative;
    z-index: 1;
  }

  /* Overlay for better readability */
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

<!-- Main Container -->
<div class="container mt-5 pt-5">

  <div class="row align-items-center mb-5" data-aos="fade-up">
    <div class="col-md-8">
      <h2 class="mb-3">About Me</h2>
      <p>
  I am currently a Ph.D. candidate in the field of physics, pursuing my doctoral studies at Jagiellonian University in Krakow, Poland, under the guidance of 
  <span style="color:cyan; font-weight:bold;">Professor Krzysztof Sacha</span>. 
  My primary area of research revolves around the fascinating concept of <strong>Time Crystals</strong>.
</p>

<p>
  In our research group, we explore a diverse range of systems where we engineer the time-dependent components of the Hamiltonian to unlock unique phases and phenomena in the time domain. 
  Some part of this research is already published as a letter in 
  <span style="color:red; font-style:italic;">Phys. Rev. A</span> and 
  <span style="color:red; font-style:italic;">Phys. Rev. R</span>. 
  This exciting work has led to collaborations with esteemed researchers in the field.
</p>

<p>
  During my Ph.D., I had the privilege of collaborating with 
  <span style="color:cyan; font-weight:bold;">Professor Lingzhen Guo</span> from the Max Planck Institute. 
  Together, we delved into the stability of phase space crystals, particularly in the presence of dissipation and temperature effects. 
  Some of our findings from this collaboration were published in 
  <span style="color:red; font-style:italic;">Phys. Rev. B</span>.
</p>

<p>
  Another intriguing aspect of my research involves the creation of condensed matter phases within photonic systems. 
  In collaboration with 
  <span style="color:cyan; font-weight:bold;">Professor Almut Beige</span> from the University of Leeds, 
  <span style="color:cyan; font-weight:bold;">Professor Hossein Taheri</span> from the University of California, and 
  <span style="color:cyan; font-weight:bold;">Professor Andrey Matsko</span> from NASA, 
  we explored the emergence of <strong>photonic time crystals</strong>. 
  This innovative approach harnesses periodic changes in the refractive index over both time and space dimensions, leading to the creation of a novel system with intriguing band structures. 
  This study is available in 
  <span style="color:red;">arXiv:2409.07885v1</span> (submitted to <em>Phys. Rev. L</em>). 
  The next study we consider in the photonic system is the Anderson localization in a photonic time crystal. 
  The study is available in 
  <span style="color:red;">arXiv:2410.23095</span> (submitted to <em>Phys. Rev. L</em>).
</p>

<p>
  In my master's studies, we focused on an interacting spinless fermionic system. 
  Our investigations revealed that in our system, the weak breaking of ergodicity leads to the formation of the scarred state, resulting in the formation of the discrete-time crystal. 
  Some part of this work, in collaboration with 
  <span style="color:cyan; font-weight:bold;">Dr. Hadi Yarloo</span>, 
  was published in 
  <span style="color:red;">Phys. Rev. B</span>.
</p>

<p>
  My master's thesis prominently features the study of quantum phase transitions, with an emphasis on employing machine learning algorithms. 
  I conducted in-depth research on the quantum Ising model in the presence of transfer fields and next-nearest neighbor interactions, utilizing a <strong>Feedforward Neural Network</strong>. 
  Furthermore, we explored the phase transition from the Eigenstate Thermalization Hypothesis (ETH) to the Discrete-Time Crystal (DTC) by applying <strong>Recurrent Neural Networks</strong>.
</p>

<p>
  This multifaceted journey through the realms of quantum many-body systems, time crystals, thermalization in quantum systems, and the application of neural networks in quantum systems 
  has been a remarkable part of my academic pursuits, shaping my path as a dedicated researcher in the field of physics.
</p>
      <p>I am currently a Ph.D. student in physics at the <strong>Jagiellonian University</strong>, Krakow, Poland, working with 
      <a href="https://chaos.if.uj.edu.pl/~sacha/" target="_blank">Prof. Krzysztof Sacha</a>. My research focuses on 
      <strong>Time Crystalline behavior</strong> and modern quantum systems. You can find the list of my publications in <a href="https://scholar.google.com/citations?user=ooL_O7sAAAAJ&hl=en" target="_blank">Google Scholar</a>.</p>
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
<!-- Floating Side Box -->
<div class="floating-box">
  <h5 class="text-white">Quick Links</h5>
  <a href="https://aliemami94.github.io/pages/research.html" target="_blank" class="box-link">🧪 Research</a><br>
  <a href="https://aliemami94.github.io/pages/teaching.html" target="_blank" class="box-link">📘 Teaching</a>
</div>
