---
permalink: /
title: ""
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


<h2>Research Areas</h2>

<div class="research-grid">

  <a class="research-card"
     href="/research/#scientific-machine-learning">
    <img src="/images/figure1.png"
         alt="Scientific Machine Learning">
    <h3>Scientific Machine Learning for PDEs</h3>
    <p>PINNs, variational methods, neural operators,
       and physics-informed learning.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#power-energy">
    <img src="/images/figure2.png"
         alt="AI for Power and Energy Systems">
    <h3>AI for Power and Energy Systems</h3>
    <p>Lightning localization, peak-current estimation,
       and power-system protection.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#biomedical">
    <img src="/images/figure3.png"
         alt="AI for Biomedical Electromagnetics">
    <h3>AI for Biomedical Electromagnetics</h3>
    <p>Generative models for patient-specific TMS,
       MRI-based planning, and coil positioning.</p>
    <span class="research-link">Explore Research →</span>
  </a>

  <a class="research-card"
     href="/research/#geophysics">
    <img src="/images/figure4.png"
         alt="Geophysical Inversion">
    <h3>Geophysical Inversion and Scientific Computing</h3>
    <p>AI-based geophysical inversion, electrical
       resistivity tomography, and conductivity mapping.</p>
    <span class="research-link">Explore Research →</span>
  </a>

</div>



<style>
/* Selected Research Contributions */

.contribution-card {
  border: 1px solid #7775;
  border-radius: 12px;
  padding: 24px;
  margin: 24px 0;
  transition: border-color .25s ease,
              box-shadow .25s ease,
              transform .25s ease;
}

.contribution-card:hover {
  border-color: #3b82f6;
  box-shadow: 0 6px 22px rgba(59,130,246,.12);
  transform: translateY(-3px);
}

.contribution-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 12px;
  margin-bottom: 12px;
}

.contribution-number {
  font-size: .78rem;
  letter-spacing: .08em;
  opacity: .65;
  font-weight: 600;
}

.contribution-year {
  font-size: .78rem;
  padding: 4px 12px;
  border: 1px solid #7775;
  border-radius: 20px;
}

.contribution-card h3 {
  margin: 0 0 12px;
  font-size: 1.3rem;
  font-weight: 600;
}

.contribution-card p {
  font-size: .94rem;
  line-height: 1.65;
  margin-bottom: 18px;
}

.contribution-card img {
  display: block;
  width: 100%;
  max-width: 600px;
  height: auto;
  margin: 16px auto 22px;
  border-radius: 8px;
}

.contribution-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.contribution-links a {
  display: inline-block;
  padding: 7px 14px;
  font-size: .83rem;
  border: 1px solid #7776;
  border-radius: 7px;
  text-decoration: none !important;
  color: inherit;
  transition: border-color .2s ease,
              background .2s ease;
}

.contribution-links a:hover {
  border-color: #3b82f6;
  background: rgba(59,130,246,.08);
}

@media (max-width: 600px) {
  .contribution-card {
    padding: 16px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .contribution-card,
  .contribution-links a {
    transition: none;
  }
  .contribution-card:hover {
    transform: none;
  }
}
</style>


<h2>Key Contributions</h2>

<div class="contribution-card">
  <div class="contribution-top">
    <span class="contribution-number">
      01 / SELECTED RESEARCH
    </span>
    <span class="contribution-year">2026</span>
  </div>

  <h3>INI-VPINN</h3>

  <p>
    A variational PINN framework with implicit treatment
    of Neumann and interface conditions for multi-material
    domains with complex geometries.
  </p>

  <img src="/images/INIVPINN.gif"
       alt="INI-VPINN numerical simulation"
       loading="lazy">

  <div class="contribution-links">
    <a href="https://arxiv.org/abs/2606.18032">
      arXiv ↗
    </a>
    <a href="https://www.sciencedirect.com/science/article/pii/S0021999126006777">
      Elsevier ↗
    </a>
    <a href="https://github.com/ShayanDodge/INI-VPINN">
      GitHub ↗
    </a>
  </div>
</div>

<div class="contribution-card">
  <div class="contribution-top">
    <span class="contribution-number">
      02 / SELECTED RESEARCH
    </span>
    <span class="contribution-year">2025</span>
  </div>

  <h3>STAR-PINN</h3>

  <p>
    A STacked Adaptive Residual PINN approach for
    time-domain magnetic diffusion in nonlinear materials.
  </p>

  <img src="/images/STARPINN_V2.gif"
       alt="STAR-PINN numerical simulation"
       loading="lazy">

  <div class="contribution-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/11122441">
      Paper ↗
    </a>
    <a href="https://github.com/ShayanDodge/star-pinn-magnetic-diffusion">
      GitHub ↗
    </a>
    <a href="https://shayandodge.com/posts/2026/06/star-pinn-v1-0-0/">
      Read more ↗
    </a>
  </div>
</div>

<div class="contribution-card">
  <div class="contribution-top">
    <span class="contribution-number">
      03 / SELECTED RESEARCH
    </span>
    <span class="contribution-year">2024</span>
  </div>

  <h3>Hybrid BEM–PINN</h3>

  <p>
    A hybrid Boundary Element–Physics-Informed Neural
    Network method for electromagnetic analysis.
  </p>

  <img src="/images/BEMPINN.gif"
       alt="Hybrid BEM-PINN numerical simulation"
       loading="lazy">

  <div class="contribution-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/10755077">
      Paper ↗
    </a>
    <a href="https://github.com/ShayanDodge/Hybrid-BEM-PINN-Electromagnetics">
      GitHub ↗
    </a>
    <a href="https://shayandodge.com/posts/2026/04/Hybrid-BEM-PINN-Electromagnetics-v1-0-0/">
      Read more ↗
    </a>
  </div>
</div>


---

## Academic Activities

Alongside my research, I contribute to journal editorial service and peer review, conference organization, teaching, and undergraduate thesis supervision at the University of Pisa.

[Explore Academic Activities →](/academic-activities/)


---
## Recent News

- **[08/2026]** Our work on <a href="https://doi.org/10.1016/j.jcp.2026.115328">INI-VPINN</a> has been published in the Journal of Computational Physics (JCP). [<a href="https://arxiv.org/abs/2606.18032">arXiv</a>] [<a href="https://www.sciencedirect.com/science/article/pii/S0021999126006777?dgcid=author">Elsevier</a>]

- **[06/2026]** Participated in <a href="https://aces-society.org/conference/Greece_2026/">ACES 2026</a> and <a href="https://cefc2026.gr/">CEFC 2026</a> in Thessaloniki, Greece, contributing to five works spanning Scientific Machine Learning, Physics-Informed Neural Networks, Computational Electromagnetics and Biomedical Engineering.


- **[05/05/2026]** Joined the <i>IEEE Journal on Multiscale and Multiphysics Computational Techniques (JMMCT)</i> as a <b>Student Editorial Assistant</b>. Excited to contribute to the journal and further develop my research and editorial experience. [<a href="https://ieee-jmmct.org/editorial-board/#student-editorial-assistants">IEEE JMMCE</a>]

- **[14/04/2026]** Our paper, <a href="https://doi.org/10.1108/COMPEL-10-2025-0508">“PINN-based resolution of inverse non-linear magnetostatic problems,”</a> has been published in COMPEL.

---