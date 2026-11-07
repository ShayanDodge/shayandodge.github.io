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
</style>


My research lies at the intersection of **scientific machine learning**, **computational electromagnetics**, and **AI for physics**. I develop physics-informed and data-driven numerical approaches for electromagnetic forward and inverse problems, with applications in power systems, biomedical engineering, and geophysical imaging.

<span id="scientific-machine-learning" class="research-anchor"></span>
<h2>Scientific Machine Learning for PDEs</h2>

I investigate physics-informed neural networks (PINNs), variational and weak-form formulations, and neural operators for solving and accelerating electromagnetic partial differential equations.


**Selected research:**

- **Neural Operators:** Physics-informed operator learning
  for parametric electromagnetic modeling, surrogate
  simulation, and efficient prediction of electromagnetic
  field distributions.

  **1. Physics-Informed Fourier Neural Operators (PI-FNO) for Nonlinear Magnetoquasistatic Analysis**

  This work develops a physics-informed Deep Operator
  Network for parametric modeling of electromagnetic
  devices, covering linear and nonlinear magnetostatics,
  frequency-domain magnetoquasistatics, and time-domain
  magnetoquasistatic problems.

  The framework incorporates physical governing equations,
  boundary conditions, and material interface constraints
  into operator learning, reducing the need for large
  labeled datasets.

  <!-- Add your figure after uploading it:
  <div align="center">
    <img src="/images/PIFNO.png"
         alt="PI-DeepONet results"
         style="width:100%;max-width:600px;height:auto;">
  </div>
  -->
  [Paper](https://ieeexplore.ieee.org/document/11774833) 
  

  **2. Neural Operator Research — Paper 2**

  [Add a short description of the method, the physical
  problem studied, and the main contribution of Paper 2.]

  <!-- Add your figure after uploading it:
  <div align="center">
    <img src="/images/neural-operator-paper2.png"
         alt="Neural operator Paper 2 results"
         style="width:100%;max-width:600px;height:auto;">
  </div>
  -->
  [Paper](https://ieeexplore.ieee.org/document/11717591)

  **3. Neural Operator Research — Paper 3**

  [Add a short description of the method, the physical
  problem studied, and the main contribution of Paper 3.]

  <!-- Add your figure after uploading it:
  <div align="center">
    <img src="/images/neural-operator-paper3.png"
         alt="Neural operator Paper 3 results"
         style="width:100%;max-width:600px;height:auto;">
  </div>
  -->
  [Paper](https://ieeexplore.ieee.org/document/11653419)


- **INI-VPINN:** Variational PINNs with implicit Neumann
  and interface handling in multi-material domains.
  [Paper](https://arxiv.org/abs/2606.18032) ·
  [Code](https://github.com/ShayanDodge/INI-VPINN)

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
