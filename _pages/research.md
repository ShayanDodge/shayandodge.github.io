---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-anchor {
  display: block;
  position: relative;
  top: -120px;
  visibility: hidden;
  height: 0;
}

html {
  scroll-behavior: smooth;
}


.neural-work {
  margin: 1.5rem 0 2rem;
  padding: 22px;
  border: 1px solid #e2e5e9;
  border-radius: 12px;
  background: transparent;
}

.neural-work h4 {
  margin-top: 0;
  margin-bottom: 14px;
  font-weight: 600;
}

.neural-work figure {
  margin: 1.5rem auto;
  text-align: center;
}

.neural-work figure img {
  display: block;
  width: 100%;
  max-width: 650px;
  height: auto;
  margin: 0 auto;
  border-radius: 8px;
}

.neural-work figcaption {
  margin-top: 10px;
  font-size: 0.85rem;
  color: #777;
  line-height: 1.5;
}

.neural-work a {
  text-decoration: none;
}

.neural-work a:hover {
  text-decoration: underline;
}


.ini-work {
  margin: 1.5rem 0 2rem;
  padding: 22px;
  border: 1px solid #e2e5e9;
  border-radius: 12px;
}

.ini-work h4 {
  margin-top: 0;
}

.ini-work figure {
  margin: 1.5rem auto;
  text-align: center;
}

.ini-work figure img {
  display: block;
  max-width: 680px;
  width: 100%;
  height: auto;
  margin: 0 auto;
  border-radius: 8px;
}

.ini-work figcaption {
  font-size: 0.85rem;
  color: #777;
  margin-top: 10px;
  line-height: 1.5;
}

</style>

My research lies at the intersection of **scientific machine learning**, **computational electromagnetics**, and **AI for physics**. I develop physics-informed and data-driven numerical approaches for electromagnetic forward and inverse problems, with applications in power systems, biomedical engineering, and geophysical imaging.

<span id="scientific-machine-learning" class="research-anchor"></span>
<h2>Scientific Machine Learning for PDEs</h2>

I investigate physics-informed neural networks (PINNs), variational and weak-form formulations, and neural operators for solving and accelerating electromagnetic partial differential equations.


**Selected research:**


<h3>Neural Operators for Computational Electromagnetics</h3>

<p>
This research line investigates physics-informed neural
operators for parametric electromagnetic modeling,
surrogate simulation, and efficient prediction of
electromagnetic field distributions.
</p>

<div class="neural-work">

  <h4>1. Physics-Informed Fourier Neural Operators (PI-FNO)</h4>

  <p>
  A physics-informed Fourier neural operator framework
  for time-domain magnetoquasistatic analysis of nonlinear
  electromagnetic devices. PI-FNO predicts magnetic vector
  potential distributions across varying excitation
  currents and frequencies, accounting for nonlinear
  magnetic materials and eddy currents. Validated on a
  2D inductor benchmark, it achieves an average NRMSE
  of 2.6% and reduces prediction error by more than 66%
  compared with parametric PINNs.
  </p>

  <figure>
    <img src="/images/PIFNO.png"
         alt="PI-FNO framework and numerical results"
         loading="lazy">
    <figcaption>
      PI-FNO framework and numerical results for nonlinear
      magnetoquasistatic analysis.
    </figcaption>
  </figure>

  <p>
    <a href="https://ieeexplore.ieee.org/document/11774833">
      Paper
    </a>
  </p>

</div>

<div class="neural-work">

  <h4>2. PI-DeepONet for Wireless Power Transfer Coil Coupling</h4>

  <p>
  A hybrid physics-informed and data-driven neural
  operator framework for fast parametric modeling of
  wireless power transfer systems. By combining Maxwell's
  equations with FEM-generated data and Fourier-based
  field decomposition, PI-DeepONet predicts magnetic
  field distributions under varying coil misalignments
  and air-gap conditions, achieving a relative L2 error
  below 2.6% in magnetic vector potential prediction.
  </p>

  <figure>
    <img src="/images/WPT.png"
         alt="PI-DeepONet wireless power transfer results"
         loading="lazy">
    <figcaption>
      Parametric electromagnetic field prediction for
      wireless power transfer systems.
    </figcaption>
  </figure>

  <p>
    <a href="https://ieeexplore.ieee.org/document/11717591">
      Paper
    </a>
  </p>

</div>

<div class="neural-work">

  <h4>3. PI-DeepONet for Parametric Electromagnetic Modeling</h4>

  <p>
  A physics-informed neural operator framework for
  efficient parametric modeling of electromagnetic
  devices, spanning linear and nonlinear magnetostatics
  to frequency- and time-domain magnetoquasistatics.
  By incorporating Maxwell's equations, boundary
  conditions, and material interface constraints into
  the learning process, PI-DeepONet enables physically
  consistent, data-efficient prediction of
  electromagnetic fields.
  </p>

  <!-- Uncomment after uploading your third figure:

  <figure>
    <img src="/images/PIDeepONet.png"
         alt="PI-DeepONet electromagnetic modeling results"
         loading="lazy">
    <figcaption>
      PI-DeepONet predictions for parametric
      electromagnetic modeling.
    </figcaption>
  </figure>

  -->

  <p>
    <a href="https://ieeexplore.ieee.org/document/11653419">
      Paper
    </a>
  </p>

</div>

  
<h3>INI-VPINN: Variational Physics-Informed Learning</h3>

<p>
This research line investigates variational physics-informed
neural networks for solving partial differential equations
in complex geometries and multi-material domains.
</p>

<div class="ini-work">

  <h4>1. INI-VPINN — Original Framework</h4>

  <p>
  The INI-VPINN framework employs a variational
  physics-informed formulation to implicitly enforce
  Neumann boundary and material interface conditions.
  It avoids additional penalty terms or separate
  subdomain networks, providing a unified approach
  to solving PDEs in heterogeneous domains.
  </p>

  <figure>
    <img src="/images/INIVPINN.gif"
         alt="Original INI-VPINN framework"
         loading="lazy">
    <figcaption>
      Original INI-VPINN framework and numerical results.
    </figcaption>
  </figure>

  <p>
    <a href="https://arxiv.org/abs/2606.18032">
      Paper
    </a>
    &nbsp;·&nbsp;
    <a href="https://github.com/ShayanDodge/INI-VPINN">
      GitHub
    </a>
  </p>

</div>

<div class="ini-work">

  <h4>2. INI-VPINN — Follow-up Research</h4>

  <p>
  [Insert a concise explanation of the follow-up
  contribution, the new method, and its numerical
  validation.]
  </p>

  <figure>
    <img src="/images/ini-vpinn-child.png"
         alt="Follow-up research results"
         loading="lazy">
    <figcaption>
      Follow-up method and numerical results.
    </figcaption>
  </figure>

  <p>
    <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=1usufq0AAAAJ&amp;citation_for_view=1usufq0AAAAJ:MXK_kJrjxJIC">
      Paper
    </a>
  </p>

</div>

- **STAR-PINN:** Stacked adaptive residual PINNs for
  nonlinear magnetic diffusion.
  [Paper](https://doi.org/10.1109/ACCESS.2025.3597869) ·
  [Code](https://github.com/ShayanDodge/star-pinn-magnetic-diffusion)

- **Hybrid BEM–PINN:** Boundary element methods combined
  with physics-informed learning for electromagnetic
  problems.
  [Paper](https://doi.org/10.1109/ACCESS.2024.3500039) ·
  [Code](https://github.com/ShayanDodge/Hybrid-BEM-PINN-Electromagnetics)




<span id="power-energy-systems" class="research-anchor"></span>
<h2>AI for Power and Energy Systems</h2>

Within the **FELINES** research project, I developed machine-learning approaches to lightning localization, peak-current estimation, and lightning-induced overvoltage prediction, supporting computational tools for power-system protection.

**Selected research:**

- [Deep-learning lightning location paper](https://doi.org/10.1016/j.epsr.2025.111437)
- [FELINES open-source project](https://github.com/ShayanDodge/FELINES-Lightning-Forecast)
- [FELINES research program](https://felines.prin.unige.it/)

<span id="biomedical-electromagnetics" class="research-anchor"></span>
<h2>AI for Biomedical Electromagnetics</h2>

My research includes generative learning and inverse modeling for patient-specific transcranial magnetic stimulation (TMS), as well as deep-learning surrogate models for rapid assessment of specific absorption rate (SAR) in electromagnetic devices.

**Selected research:**

- **STEM-DEEP:** Generative electric-field modeling and inverse coil-placement optimization for TMS. [Research program](https://cad.unipv.it/PRIN/prin.html)
- **SAR surrogate modeling:** Rapid prediction of SAR hotspots. [Paper](https://doi.org/10.1049/smt2.70009)

<span id="geophysical-inversion" class="research-anchor"></span>
<h2>Geophysical Inversion and Scientific Computing</h2>

My work on **AIGEO** focuses on physics-informed and data-driven approaches to geophysical electromagnetic inverse problems, including electrical resistivity tomography (ERT). My scientific-computing background also includes GPU-accelerated FDTD simulation for wave propagation in plasma.

**Selected research:**

- **AIGEO:** AI for electromagnetic geophysical inversion (ongoing research)
- **GPU-accelerated FDTD:** Electromagnetic wave propagation in plasma. [Preprint](https://arxiv.org/abs/2211.05647)

---

For research announcements, visit my [blog](/year-archive/). For my full academic record, see the [CV](/files/Shayan_CV%20(full).pdf).
