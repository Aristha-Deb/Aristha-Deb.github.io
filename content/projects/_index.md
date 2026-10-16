---
title: Projects
summary: Computational projects in generative modeling and optimal transport.
type: landing

sections:
  - block: markdown
    id: projects-banner
    content:
      title: ""
      text: |-
        ![Sunset landscape from the original Projects page](images/source/projects-b.jpg)
    design:
      css_class: "page-banner section-divider"
      columns: "1"
  - block: markdown
    id: wasserstein-gan
    content:
      title: Wasserstein Adversarial Generative Network for Optimal Transport
      text: |-
        Designed and programmed a Wasserstein Generative Adversarial Network (WGAN) that trains from the MNIST dataset and maps Gaussian noise to realistic handwritten digits. PyTorch and NumPy were used with GPU-friendly integrations.

        ![Generated handwritten digits from the WGAN project](images/source/projects-c.png)
    design:
      css_class: section-divider
      columns: "1"
  - block: markdown
    id: neural-odes
    content:
      title: Neural ODEs for continuous optimal transport
      text: |-
        Implemented a neural ODE in Python to solve the well-known Benamou–Brenier optimal transport problem. The program uses an RK4 solver together with classic PyTorch packages. The Gaussian distribution is smoothly transported to the desired digit.

        ![Animated optimal transport visualization from the Neural ODE project](images/source/projects-a.gif)
    design:
      columns: "1"
---
