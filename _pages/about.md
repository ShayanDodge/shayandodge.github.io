---
permalink: /
title: "Shayan Dodge"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---

## About Me

Shayan Dodge works at the intersection of computational electromagnetics and artificial intelligence. His research integrates high-fidelity numerical methods, including the finite element method (FEM), finite-difference time-domain (FDTD), and boundary element method (BEM), with physics-informed neural networks to develop scalable, physics-consistent surrogate models for electromagnetic systems. 

His work aims to advance next-generation machine learning frameworks that enable real-time electromagnetic analysis and design optimization in complex multiphysics environments. His research is carried out under the supervision of <a href="https://destec.unipi.it/en/user/13">Prof. Sami Barmada</a>.

---

## Key Contributions

**Physics-Informed Neural Networks for Electromagnetic Problems**  
  Classical electromagnetic (EM) solvers—such as FEM, FDTD, and BEM—can become computationally expensive when applied to complex geometries or inverse problems. Physics-Informed Neural Networks (PINNs) provide a promising alternative by learning solutions directly from the governing equations, thereby reducing reliance on mesh generation and large-scale simulations. Within this framework, my research contributions include:

  - Adaptive residual PINN (STAR-PINN) for time-domain magnetic diffusion [<a href="https://ieeexplore.ieee.org/abstract/document/11122441">Paper</a>][GitHub]
  - Hybrid Boundary Element–PINN Method for Electromagnetic Analysis [<a href="https://ieeexplore.ieee.org/abstract/document/10755077">Paper</a>][GitHub]
  

**Forecasting Lightning Effects in Electrical Systems (<a href="https://felines.prin.unige.it/">FELINES</a>)**  
  FELINES is a research project aiming to design a preventive protection concept for electrical infrastructures by sensing electromagnetic fields generated during the early phases of lightning inception—in particular the Preliminary Breakdown Pulses (PBP)—and using them to predict whether the upcoming Return Stroke (RS) could be dangerous, enabling timely disconnection of vulnerable equipment. The work combines PBP/RS modeling, electromagnetic field & coupling simulations, and machine learning for early classification (“dangerous RS” vs “not dangerous”). More information is available on the <a href="https://felines.prin.unige.it/">project website</a> and <a href="https://github.com/ShayanDodge/FELINES-Lightning-Forecast">GitHub</a> repository.

**AI-Based Optimization of Transcranial Magnetic Stimulation (TMS)**  
  The goal of this work is to develop a data-driven framework for determining the optimal transcranial magnetic stimulation (TMS) coil position and stimulation intensity to achieve targeted brain stimulation. The approach integrates MRI-based personalized brain models with electromagnetic simulations using the finite element method (FEM) to compute induced electric fields, combined with model order reduction (MOR) techniques to enable fast evaluations. To address the inverse problem, deep learning models—specifically a combination of variational autoencoders (VAE) and convolutional neural networks (CNN)—are employed to predict optimal coil configurations efficiently. This framework supports applications in personalized TMS therapy, optimization of brain stimulation protocols, treatment planning for neurological and psychiatric disorders, and advanced bioelectromagnetic modeling. Further details, datasets, and implementation resources are available on the <a href="https://cad.unipv.it/PRIN/project.html">project website</a>.

---

## Recent News

- **[4/2026]** 

---