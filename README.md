# ABOUT THIS REPOSITORY

This repository consists of simplified architectures of the LLMs we use today.  \
To name them, we have :  \

1. A GPT-style Large Language Model (LLM) with 163 million parameters,  implementing token and absolute positional embeddings, stacked Transformer blocks with causal Multi-Head Self-Attention, residual connections, Layer Normalization, GeLU-activated Feed-Forward Networks, a final Layer Normalization layer, and a language modeling head for next-token prediction.
   
2. A LLaMA-style Large Language Model (LLM) with 183 million parameters, implementing Rotary Positional Embeddings (RoPE), Grouped Query Attention (GQA), RMS Normalization, SwiGLU-activated Feed-Forward Networks, residual connections, and an autoregressive language modeling head for next-token prediction.
   
3. A Simplified DeepSeek-style Large Language Model (LLM) with 445 million parameters, implementing Rotary Positional Embeddings (RoPE), Multi-Head Latent Attention (MLA), RMS Normalization, a Mixture-of-Experts (MoE) feed-forward architecture with top-k routing, SwiGLU-activated expert networks, residual connections, and a language modeling head for next-token prediction.

Feel free to explore the implementations, experiment with them, and share any feedback or suggestions. I'm always happy to learn and improve !

