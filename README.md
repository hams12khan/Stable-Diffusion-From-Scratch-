# 🧠 Stable Diffusion – Rebuilt from Scratch

*A modular and educational deep dive into the core mechanics of Stable Diffusion—built from scratch using PyTorch, with plug-and-play support for Hugging Face weights.*

![A cat stretching on the floor, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution.](![output](https://github.com/user-attachments/assets/778e85a8-5a77-4e1b-be9a-ad3590da3594)
)

---

## 📌 Project Overview

This repository contains a fully custom implementation of the Stable Diffusion architecture, including:

- 🔧 Custom-built **UNet**, **Variational Autoencoder (VAE)**, and **DDPM sampling logic**
- 💬 **CLIP Text Encoder** integration using the tokenizer from `transformers`
- 🧠 Educational layout for understanding diffusion models at a fundamental level
- ⚡ Practical image generation using **pre-trained weights** from `sd-legacy/stable-diffusion-v1-5` via Hugging Face's `diffusers`

Whether you're here to learn, extend, or experiment—this repo is designed for **clarity**, **modularity**, and **insight**.

---

## 🚀 Features

### ✅ Custom Implementations

- **UNet**: Denoising network with time embeddings and attention blocks  
- **VAE**: Encoder-decoder to compress images into latent space and reconstruct  
- **CLIP Encoder**: Textual prompt encoder for conditional generation  
- **DDPM (Denoising Diffusion Probabilistic Models)**: Sampling, noise scheduling, and inference logic  

### 🔁 Pre-Trained Weight Support

- Load pretrained weights from `sd-legacy/stable-diffusion-v1-5` via Hugging Face for fast inference
- Combine your architecture with industry-grade weights for benchmarking

---
