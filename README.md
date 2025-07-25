# infovae-seminar

This repository accompanies our LMU seminar on InfoVAE and its extensions (see Zhao et al., 2019). It provides:

- **Training & Evaluation Code**  
  Implementations of InfoVAE variants and lightweight alternatives:  
  - Divergence‑based VAEs: MMD, Stein, Sinkhorn, Cramér, χ²  
  - Adaptive hyperparameter schedulers for \(\lambda\) and \(\alpha\)  
  - Lightweight VAEs: Free‑Bits VAE, BN‑VAE, ContrastiveAE, ReconAE  
- **Analysis Notebooks**  
  Jupyter notebooks illustrating:  
  - Posterior–prior alignment (RBF‑MMD)  
  - Reconstruction quality (BCE)  
  - Semi‑supervised classification error  
  - Wall‑clock training time  
- **Paper & Slides**  
  `InfoVAE.pdf` contains the main write‑up; slides and supplementary figures are included.

> **Note:** We reviewed the PyTorch reimplementation at  
> https://github.com/Saswatm123/MMD-VAE  
> but did not incorporate its code directly.

## Reference  
Zhao, S., Song, J., & Ermon, S. (2019). *InfoVAE: Information Maximizing Variational Autoencoders*.  
