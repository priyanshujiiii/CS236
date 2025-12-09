# Advanced Generative Modeling (PyTorch + MNIST)

This repository is a **collection of Jupyter notebooks** covering the full theory and practical implementation of **advanced generative models**.  
All implementations are done **purely in PyTorch**, and all experiments use the **MNIST dataset** for clarity and simplicity.

The notebooks focus heavily on **Diffusion Models**, but also include foundational topics such as GANs, VAEs, Auto-Regressive Models, and Preference Optimization.

---

# Notebook Structure (All 56 Lessons)

Below is the complete list of notebooks included in this repository.

---

## **Module 1: Foundations of Generative AI**
1. Basics of Generative Modeling  
2. f-Divergence  
3. Variational Divergence Minimization  
4. Generative Modeling via Divergence Minimization  
5. Jensen's Inequality (Derivation + Intuition)

---

## **Module 2: Generative Adversarial Networks (GANs)**
6. Introduction to GANs  
7. GANs as Classifier-Guided Generative Models  
8. Deep Convolutional GAN (DCGAN) on MNIST  
9. Conditional GANs (cGANs)  
10. Wasserstein GAN (WGAN + WGAN-GP)  
11. Bi-Directional GANs (BiGAN / ALI)  
12. Latent Regression & GAN Inversion  
13. Domain Adversarial Networks (DANN)  
14. Evaluation Metrics for Generative Models (FID, IS)

---

## **Module 3: Latent Variable Models & VAEs**
15. Introduction to Latent Variable Models  
16. Gaussian Mixture Models (Expectation-Maximization)  
17. Evidence Lower Bound (ELBO)  
18. Variational Autoencoder (VAE) Theory  
19. Reparameterization Trick (Derivation)  
20. Implementing VAEs in PyTorch (MNIST)  
21. Sampling & Inference with VAEs  
22. β-VAE  
23. Vector-Quantized VAE (VQ-VAE)

---

## **Module 4: Diffusion Models (DDPMs) — Main Focus**
24. Introduction to Diffusion Models  
25. Forward (q) and Reverse (p) Processes  
26. Derivation of DDPM ELBO  
27. Simplified DDPM Loss & Optimization  
28. ELBO Equivalence (Proof)  
29. Training DDPM in PyTorch (MNIST)  
30. U-Net Backbone for Diffusion Models  
31. Sampling & Inference in DDPM  
32. Full DDPM Implementation (MNIST)  
33. Alternate Interpretations of Diffusion Models  
34. Score Matching & Score-Based Models  
35. Guided Diffusion (Classifier & Classifier-Free)  
36. Latent Diffusion Models (LDM — MNIST latent space)  
37. Denoising Diffusion Implicit Models (DDIM)  
38. DDIM Sampling & Inference  
39. Noise Prediction Network Implementation  
40. Full DDIM Implementation (MNIST)  
41. Guided Diffusion Implementation (MNIST)

---

## **Module 5: Auto-Regressive Models & Transformers**
42. Auto-Regressive Modeling  
43. Attention Mechanism (Derivation)  
44. Transformers for Generative Modeling  
45. Transformer Architecture (MNIST flattened tokens)  
46. Residual Connections & Layer Normalization  
47. Positional Embeddings  
48. Training & Sampling from AR Models

---

## **Module 6: Reinforcement Learning for Generative Modeling**
49. Introduction to Reinforcement Learning  
50. Policy Gradient Theorem  
51. Auto-Regressive Language Models as RL Policies  
52. Proximal Policy Optimization (PPO)  
53. Trust Region Policy Optimization (TRPO)

---

## **Module 7: Preference Optimization & State-Space Models**
54. Reward Modeling  
55. Direct Preference Optimization (DPO)  
56. State-Space Models (SSM) and Sequence Generation

---

# Framework Restrictions (Important)

- **PyTorch only** — used for all models, training, and experiments  
- **MNIST only** — the dataset used across all notebooks  
- No JAX, no other datasets, no external frameworks

---

# Purpose of This Repository

This notebook collection is designed to give a **deep mathematical and implementation-level understanding** of generative modeling — especially **Diffusion Models** — using only:

- **PyTorch**  
- **MNIST**

It serves as a complete learning + reference library for anyone studying generative modeling from first principles.

