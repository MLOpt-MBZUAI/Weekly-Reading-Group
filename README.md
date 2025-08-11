# Weekly-Reading-Group
## First week paper sharing
**Date**: 2025-06-30 9:00-11:00 AM

**Topic**:Denoising Diffusion Probabilistic Models

**Abstract**：We present high quality image synthesis results using diffusion probabilistic models,
a class of latent variable models inspired by considerations from nonequilibrium
thermodynamics. Our best results are obtained by training on a weighted variational
bound designed according to a novel connection between diffusion probabilistic
models and denoising score matching with Langevin dynamics, and our models naturally admit a progressive lossy decompression scheme that can be interpreted as a
generalization of autoregressive decoding. On the unconditional CIFAR10 dataset,
we obtain an Inception score of 9.46 and a state-of-the-art FID score of 3.17. On
256x256 LSUN, we obtain sample quality similar to ProgressiveGAN. Our implementation is available at https://github.com/hojonathanho/diffusion.

**Biography**
xueran han

---

## Third week paper sharing

**Date**: 2025-07-21 9:00-11:00 AM

**Topic**: SDE Perspective of Diffusion Models, Controllable Generation, and Recent Advances

**Abstract**：This talk introduces diffusion models from the perspective of Stochastic Differential Equations (SDEs), explaining how continuous-time stochastic processes relate to discrete diffusion steps. It covers controllable generation techniques such as classifier guidance, classifier-free guidance, and conditional generation with various modalities. Additionally, the presentation highlights recent advances in diffusion models. The goal is to provide researchers and practitioners with a clear understanding of both theoretical foundations and practical approaches in diffusion-based generative modeling.

**Biography**
Zhenbang Zhang

## Fourth week paper sharing

**Date**: 2025-07-28 9:00-11:00 AM

**Topic**: Geometric graph, Generalization analysis, Manifold hypothesis, GNNs, VAE

**Abstract** We propose a graph semi-supervised learning framework for classification tasks on data manifolds. Motivated by the manifold hypothesis, we model data as points sampled from a low-dimensional manifold $M \subset \mathbb{R}^F$.
The manifold is approximated in an unsupervised manner using a Variational Autoencoder (VAE), where the trained encoder maps data to embeddings that represent their coordinates in $\mathbb{R}^F$. A geometric graph is constructed with Gaussian-weighted edges inversely proportional to distances in the embedding space, transforming the point classification problem into a semi-supervised node classification task on the graph. This task is solved using a Graph Neural Network (GNN). Our main contribution is a theoretical analysis of the statistical generalization properties of this data → manifold → graph pipeline. We prove that, under uniform sampling from $M$, the generalization gap of the semi-supervised task diminishes as the graph size increases, up to the GNN training error.
Moreover, by employing a training procedure that resamples a slightly larger graph at regular intervals, we demonstrate that the generalization gap can be reduced further—vanishing asymptotically. Finally, we validate our findings through numerical experiments on image classification benchmarks, showing the empirical effectiveness of our approach.

**Biography**
Kailong Zhao