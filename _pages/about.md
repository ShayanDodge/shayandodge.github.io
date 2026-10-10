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
.research-row {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin: 2.5rem 0;
  padding-bottom: 2rem;
  border-bottom: 1px solid #333;
}

.research-row img {
  width: 260px;
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  flex-shrink: 0;
}

.research-text {
  flex: 1;
}

.research-text h3 {
  margin-top: 0;
  margin-bottom: 0.6rem;
}

.research-text p {
  margin-bottom: 0.6rem;
}

.research-text .featured {
  margin-top: 0.5rem;
}

@media (max-width: 768px) {
  .research-row {
    flex-direction: column;
    align-items: flex-start;
  }

  .research-row img {
    width: 100%;
    max-width: 380px;
  }
}
</style>


## Research Areas

<div class="research-row">
  <img src="/images/scientific_machine_learning_for_pdes.png" alt="Scientific Machine Learning for PDEs">
  <div class="research-text">
    <h3>Scientific Machine Learning for PDEs</h3>
    <p>
      PINNs, variational PINNs, weak formulations, neural operators, DeepONet,
      and Fourier neural operators for forward and inverse PDE problems.
    </p>
    <p class="featured"><strong>Featured work:</strong> INI-VPINN, STAR-PINN, hybrid BEM–PINN, PI-FNO.</p>
    <p><a href="/research/#scientific-machine-learning">Read more →</a></p>
  </div>
</div>

<div class="research-row">
  <img src="/images/ai_for_power_and_energy_systems_workflow.png" alt="AI for Power and Energy Systems">
  <div class="research-text">
    <h3>AI for Power and Energy Systems</h3>
    <p>
      Machine-learning methods for lightning localization, peak-current estimation,
      induced overvoltages, and power-system protection.
    </p>
    <p class="featured"><strong>Featured work:</strong> FELINES and electromagnetic inverse problems.</p>
    <p><a href="/research/#power-energy">Read more →</a></p>
  </div>
</div>

<div class="research-row">
  <img src="/images/ai_for_biomedical_electromagnetics_pipeline.png" alt="AI for Biomedical Electromagnetics">
  <div class="research-text">
    <h3>AI for Biomedical Electromagnetics</h3>
    <p>
      Generative and data-driven models for biomedical electromagnetics,
      including MRI-based coil positioning and personalized TMS planning.
    </p>
    <p class="featured"><strong>Featured work:</strong> STEM-DEEP, TMS optimization, SAR prediction.</p>
    <p><a href="/research/#biomedical">Read more →</a></p>
  </div>
</div>

<div class="research-row">
  <img src="/images/geophysical_inversion_workflow_infographic.png" alt="Geophysical Inversion and Scientific Computing">
  <div class="research-text">
    <h3>Geophysical Inversion and Scientific Computing</h3>
    <p>
      AI-driven inversion methods for geophysics, using voltage and current data
      from surface electrodes to predict conductivity distributions.
    </p>
    <p class="featured"><strong>Featured work:</strong> AIGEO, ERT inversion, GPU-accelerated FDTD.</p>
    <p><a href="/research/#geophysics">Read more →</a></p>
  </div>
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