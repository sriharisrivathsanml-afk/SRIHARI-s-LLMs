# ABOUT THIS REPOSITORY

This repository consists of simplified implementations of some of the AI architectures that power modern intelligent systems.

To name them, we have:

* **A GPT-style Large Language Model (LLM)** with **163 million parameters**, implementing token and absolute positional embeddings, stacked Transformer blocks with causal Multi-Head Self-Attention, residual connections, Layer Normalization, GeLU-activated Feed-Forward Networks, a final Layer Normalization layer, and a language modeling head for next-token prediction.

* **A LLaMA-style Large Language Model (LLM)** with **183 million parameters**, implementing Rotary Positional Embeddings (RoPE), Grouped Query Attention (GQA), RMS Normalization, SwiGLU-activated Feed-Forward Networks, residual connections, and an autoregressive language modeling head for next-token prediction.

* **A Simplified DeepSeek-style Large Language Model (LLM)** with **445 million parameters**, implementing Rotary Positional Embeddings (RoPE), Multi-Head Latent Attention (MLA), RMS Normalization, a Mixture-of-Experts (MoE) feed-forward architecture with top-k routing, SwiGLU-activated expert networks, residual connections, and a language modeling head for next-token prediction.

* **A CLIP-style Vision Language Model (VLM)** implementing a Vision Transformer (ViT) image encoder, a Transformer-based text encoder, separate projection heads for mapping image and text representations into a shared embedding space, and a contrastive learning objective for learning aligned image-text representations.

Feel free to explore the implementations, experiment with them, and share any feedback or suggestions. I'm always happy to learn and improve!
