# ABOUT THIS REPOSITORY

This repository consists of simplified architectures of the AI models we use today.

To name them, we have:

A GPT-style Large Language Model (LLM) with 163 million parameters, implementing token and absolute positional embeddings, stacked Transformer blocks with causal Multi-Head Self-Attention, residual connections, Layer Normalization, GeLU-activated Feed-Forward Networks, a final Layer Normalization layer, and a language modeling head for next-token prediction.

A LLaMA-style Large Language Model (LLM) with 183 million parameters, implementing Rotary Positional Embeddings (RoPE), Grouped Query Attention (GQA), RMS Normalization, SwiGLU-activated Feed-Forward Networks, residual connections, and an autoregressive language modeling head for next-token prediction.

A Simplified DeepSeek-style Large Language Model (LLM) with 445 million parameters, implementing Rotary Positional Embeddings (RoPE), Multi-Head Latent Attention (MLA), RMS Normalization, a Mixture-of-Experts (MoE) feed-forward architecture with top-k routing, SwiGLU-activated expert networks, residual connections, and a language modeling head for next-token prediction.

A Vision Transformer (ViT) with 46 million parameters for image classification, implementing patch embeddings through convolutional projection, stacked Transformer encoder blocks with Multi-Head Self-Attention, GeLU-activated Feed-Forward Networks, and a classification head for image recognition tasks.

Feel free to explore the implementations, experiment with them, and share any feedback or suggestions. I'm always happy to learn and improve!

