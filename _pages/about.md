---
permalink: /
title: "Shayan Dodge"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---

## About Me

I am a PhD researcher in Electrical Engineering at the University of Pisa, Italy, working at the intersection of Scientific Machine Learning, Computational Electromagnetics, and AI for Physics.

My research focuses on applying AI to electromagnetic simulation, power and energy systems, bioelectromagnetics, inverse problems, and scientific computing.

I develop Physics-Informed Neural Networks (PINNs), variational PINNs, neural operators, generative AI models, and deep learning frameworks for solving PDEs, surrogate modeling, signal analysis, optimization, and simulation acceleration.

---

<!-- ## Research at a Glance


| Category | Focus |
|-----------|-----------|
| Scientific Machine Learning | PINNs, Variational PINNs, Neural Operators |
| Deep Learning | RNNs, CNNs, Autoencoders, Generative AI, Residual Networks |
| Computational Methods | FEM, FDTD, BEM |
| Applications | Computational Electromagnetics, Power Systems, Bioelectromagnetics |
| Research Topics | Inverse Problems, Optimization, Surrogate Modeling, Scientific Computing |
| Software | PyTorch, TensorFlow, JAX, MATLAB, CUDA | -->

<!-- --- -->

<!-- Insert this immediately ABOVE the existing `## Key Contributions` heading in `_pages/about.md`. -->



<style>
.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin: 2rem 0;
}

.research-card {
  display: block;
  padding: 15px;
  border: 1px solid #555;
  border-radius: 12px;
  background: transparent;
  color: inherit;
  text-decoration: none !important;
  transition: transform 0.25s ease,
              border-color 0.25s ease,
              box-shadow 0.25s ease;
}

.research-card:hover,
.research-card:focus-visible {
  transform: translateY(-5px);
  border-color: #3b82f6;
  box-shadow: 0 6px 22px rgba(59,130,246,0.20);
}

.research-card img {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 10;
  object-fit: contain;
  border-radius: 8px;
  background: white;
}

.research-card h3 {
  font-size: 1.05rem;
  line-height: 1.4;
  margin: 14px 0 8px;
  font-weight: 600;
  color: inherit;
}

.research-card:hover h3,
.research-card:focus-visible h3 {
  font-weight: 800;
}

.research-card p {
  font-size: 0.88rem;
  line-height: 1.5;
  margin: 0 0 10px;
}

.research-link {
  color: #60a5fa;
  font-size: 0.88rem;
  font-weight: 600;
}

.research-card:hover .research-link {
  text-decoration: underline;
}

@media (max-width: 650px) {
  .research-grid {
    grid-template-columns: 1fr;
  }
}

@media (prefers-reduced-motion: reduce) {
  .research-card {
    transition: none;
  }
  .research-card:hover {
    transform: none;
  }
}
</style>



## Research Areas


<h2>Research Areas</h2>

<div class="research-grid">

  <a class="research-card"
     href="/research/#scientific-machine-learning">
    <img src="/images/scientific_machine_learning_for_pdes.png"
         alt="Scientific Machine Learning">
    <h3>Scientific Machine Learning for PDEs</h3>
    <p>PINNs, variational methods, neural operators,
       and physics-informed learning.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#power-energy">
    <img src="/images/ai_for_power_and_energy_systems_workflow.png"
         alt="AI for Power and Energy Systems">
    <h3>AI for Power and Energy Systems</h3>
    <p>Lightning localization, peak-current estimation,
       and power-system protection.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#biomedical">
    <img src="/images/ai_for_biomedical_electromagnetics_pipeline.png"
         alt="AI for Biomedical Electromagnetics">
    <h3>AI for Biomedical Electromagnetics</h3>
    <p>Generative models for patient-specific TMS,
       MRI-based planning, and coil positioning.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#geophysics">
    <img src="/images/geophysical_inversion_workflow_infographic.png"
         alt="Geophysical Inversion">
    <h3>Geophysical Inversion and Scientific Computing</h3>
    <p>AI-based geophysical inversion, electrical
       resistivity tomography, and conductivity mapping.</p>
    <span class="research-link">Explore Research →</span>
  </a>

</div>


## Key Contributions

**Physics-Informed Neural Networks (PINNs)**  
  PINNs combine machine learning with governing physical laws, providing a powerful framework for solving scientific and engineering problems. My research contributions in this area include:

  - **INI-VPINN**: A variational PINN framework with implicit treatment of Neumann and interface conditions for multi-material domains with complex geometries [<a href="https://arxiv.org/abs/2606.18032">arXiv</a>][<a href="https://www.sciencedirect.com/science/article/pii/S0021999126006777?dgcid=author">Elsevier</a>][<a href="https://github.com/ShayanDodge/INI-VPINN">GitHub</a>]

  <!-- ![INIVPINN](/images/INIVPINN.gif) -->
  <div align="center">
  <img src="/images/INIVPINN.gif" alt="INIVPINN" width="600">
  </div>
  [Read more ...]

  - A **S**Tacked **A**daptive **R**esidual **PINN** (**STAR-PINN**) for time-domain magnetic diffusion [<a href="https://ieeexplore.ieee.org/abstract/document/11122441">Paper</a>][<a href="https://github.com/ShayanDodge/star-pinn-magnetic-diffusion">GitHub</a>][<a href="https://www.linkedin.com/feed/update/urn:li:activity:7460580932610252800/">LinkedIn</a>]

  <!-- ![STAR-PINN Architecture](/images/STARPINN_V2.gif) -->
  <div align="center">
  <img src="/images/STARPINN_V2.gif" alt="STAR-PINN" width="600">
  </div>
  [<a href="https://shayandodge.com/posts/2026/06/star-pinn-v1-0-0/">Read more ...</a>]

  - **BEM-PINN**: Hybrid Boundary Element–PINN Method for Electromagnetic Analysis [<a href="https://ieeexplore.ieee.org/abstract/document/10755077">Paper</a>][<a href="https://github.com/ShayanDodge/hybrid-bem-pinn-electromagnetics">GitHub</a>][<a href="https://www.linkedin.com/feed/update/urn:li:activity:7447168786849484801/">LinkedIn</a>]

  <!-- ![BEMPINN](/images/BEMPINN.gif) -->
  <div align="center">
  <img src="/images/BEMPINN.gif" alt="BEMPINN" width="600">
  </div>
  [<a href="https://shayandodge.com/posts/2026/04/Hybrid-BEM-PINN-Electromagnetics-v1-0-0/">Read more ...</a>]



**Forecasting Lightning Effects in Electrical Systems (<a href="https://felines.prin.unige.it/">FELINES</a>)**  
  FELINES develops signal processing and deep learning methods for analyzing FDTD-simulated lightning electromagnetic signals and assessing lightning-related risks in power systems and transmission lines. Our contributions include:

  - Lightning Geolocation and Peak Current Estimation [<a href="https://www.sciencedirect.com/science/article/pii/S0378779625000306">Paper</a>][<a href="https://github.com/ShayanDodge/FELINES-Lightning-Forecast/tree/main/Phase%201%20%E2%80%94%20Lightning%20Geolocation%20and%20Peak%20Current%20Estimation">GitHub</a>]
  
  More details are available on the <a href="https://felines.prin.unige.it/">project website</a> and <a href="https://github.com/ShayanDodge/FELINES-Lightning-Forecast">GitHub</a>.



**AI-Based Optimization of Transcranial Magnetic Stimulation (TMS)**  
  This work develops a generative AI framework for transcranial magnetic stimulation (TMS) planning. A variational autoencoder (VAE) generates desired electric field distributions from clinician-defined targets, while a convolutional neural network (CNN) predicts the corresponding coil position and stimulation parameters using MRI-based head models and FEM simulations accelerated through model order reduction (MOR).

  More details are available on the <a href="https://cad.unipv.it/PRIN/project.html">project website</a>.

---

## Recent News

- **[08/2026]** Our work on <a href="https://doi.org/10.1016/j.jcp.2026.115328">INI-VPINN</a> has been published in the Journal of Computational Physics (JCP). [<a href="https://arxiv.org/abs/2606.18032">arXiv</a>] [<a href="https://www.sciencedirect.com/science/article/pii/S0021999126006777?dgcid=author">Elsevier</a>]

- **[06/2026]** Participated in <a href="https://aces-society.org/conference/Greece_2026/">ACES 2026</a> and <a href="https://cefc2026.gr/">CEFC 2026</a> in Thessaloniki, Greece, contributing to five works spanning Scientific Machine Learning, Physics-Informed Neural Networks, Computational Electromagnetics and Biomedical Engineering.


- **[05/05/2026]** Joined the <i>IEEE Journal on Multiscale and Multiphysics Computational Techniques (JMMCT)</i> as a <b>Student Editorial Assistant</b>. Excited to contribute to the journal and further develop my research and editorial experience. [<a href="https://ieee-jmmct.org/editorial-board/#student-editorial-assistants">IEEE JMMCE</a>]

- **[14/04/2026]** Our paper, <a href="https://doi.org/10.1108/COMPEL-10-2025-0508">“PINN-based resolution of inverse non-linear magnetostatic problems,”</a> has been published in COMPEL.

---