---
title: Research
summary: Research interests in plasma physics, data assimilation, and control theory.
type: landing

sections:
  - block: markdown
    id: research-banner
    content:
      title: ""
      text: |-
        ![Moon image from the original Research page](images/source/research-b.jpg)
    design:
      css_class: page-banner
      columns: "1"
  - block: markdown
    id: plasma-physics
    content:
      title: Data assimilation and plasma physics
      text: |-
        Researching the Flux-balanced Hasegawa–Wakatani model through filtering theory and computational fluid dynamics. We apply POD/SVD for dimensionality reduction to the model using Scikit-learn PCA and solve the governing equations through numerical methods. The resulting framework describes the turbulence that occurs in highly magnetized plasma in fusion-like environments.

        ![Plasma turbulence visualization from the original site](images/source/research-a.png)

        **Reference:** Andrew J. Majda, Di Qi, and Antoine J. Cerfon. “A flux-balanced fluid model for collisional plasma edge turbulence: Model derivation and basic physical features.” *Physics of Plasmas* 25(10), 102307 (2018).
    design:
      css_class: section-divider
      columns: "1"
  - block: markdown
    id: data-assimilation-control
    content:
      title: Data assimilation and control theory
      text: |-
        Integrating Sparse Identification of Nonlinear Dynamics (SINDy) and the Ensemble Kalman Filter with adaptive inflation to predict trajectories of true signals from stochastic datasets. The resulting architecture is applied to modern chaotic dynamical systems such as the Lorenz-96 model, with the aim of improving current methods used to control a system through this approach.

        ![Chaotic dynamical system visualization from the original site](images/source/research-c.png)

        **Reference:** Brian M. de Silva et al. “PySINDy: a Python package for the sparse identification of nonlinear dynamics from data.” *arXiv* (2020). [arXiv:2004.08424](https://arxiv.org/abs/2004.08424)
    design:
      columns: "1"
---
