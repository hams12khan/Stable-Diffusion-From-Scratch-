Stable Diffusion Rebuilt from Scratch
*A modular, educational implementation of Stable Diffusion with custom UNet, VAE, CLIP encoder, and diffusion pipeline—using pre-trained weights for accessibility.*

prompt = "A cat stretching on the floor, highly detailed, ultra sharp, cinematic, 100mm lens, 8k resolution."


![output](https://github.com/user-attachments/assets/1b371ac8-1209-49c3-a839-0e12336af825)




Example output using the pipeline (weights from sd-legacy/stable-diffusion-v1-5).
📌 Project Overview
This repository contains a from-scratch implementation of Stable Diffusion's core components (UNet, VAE encoder/decoder, CLIP text encoder, and DDPM sampling), with pre-trained weights loaded for practical inference. Ideal for:

🧠 Learning how diffusion models work under the hood.

🔧 Experimenting with custom architectures or training workflows.

🖼️ Generating images with optional pre-trained weights.

Key Distinction:

All model architectures are coded manually (PyTorch).

Pre-trained weights are loaded for quick inference (from Hugging Face diffusers).


🚀 Features
Custom Implementations
UNet: Noise prediction network with time embeddings.

VAE: Variational Autoencoder (encoder/decoder) for latent space compression.

CLIP Text Encoder: Text embeddings for prompt conditioning (tokenizer from transformers).

DDPM Pipeline: Denoising and sampling logic (noise scheduling, predict_noise()).

Pre-Trained Components
Weights for UNet, VAE, and CLIP encoder loaded from sd-legacy/stable-diffusion-v1-5 via Hugging Face for demonstration.
