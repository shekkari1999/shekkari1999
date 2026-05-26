# Akhil Shekkari

AI Engineer · MS Applied Machine Learning, University of Maryland · 2026

---

I focus on two things: making LLMs go faster, and making them smarter.

Right now that means **LLM inference** — building serving systems from scratch (Triton kernels, paged KV-cache, speculative decoding, NVIDIA Dynamo) — and **post-training** — fine-tuning models for tool use and training them with reinforcement learning to become more reliable agents.

3+ years building production ML systems. Co-authored a peer-reviewed publication in *Clinical Trials* (SAGE) on generative AI at Pfizer R&D.

---

**Active projects**

- [`mini-Inference-engine-from-scratch`](https://github.com/shekkari1999/mini-Inference-engine-from-scratch) — Triton-fused FlashAttention, paged KV-cache, speculative decoding, dynamic batching
- [`llm-serving-dynamo`](https://github.com/shekkari1999/llm-serving-dynamo) — disaggregated prefill/decode and KV-aware routing with NVIDIA Dynamo; benchmarked against single-node vLLM

---

**Writing**

- [GPU Fundamentals & LLM Inference Mental Models](https://gist.github.com/shekkari1999/7a528cb092c21c256068823390ebb510) — roofline model, memory estimation, arithmetic intensity, latency
- [Context in LLMs: What Determines It, What It Costs, and What Actually Works](https://gist.github.com/shekkari1999/d70f2572267c30b99747791bfab00eb9) — architecture, extension methods, agent strategies
- [Serving LLMs with vLLM on RunPod](https://gist.github.com/shekkari1999/3beea10ade914e62a8b41313f06719c0) — PagedAttention, continuous batching, cost benchmarks
- [A Guide to Fine-tuning Methods in LLMs](https://gist.github.com/shekkari1999/cbcfa06f8ff14138188794ce1686dbc6) — LoRA, QLoRA, PEFT, SVD intuition
- [Understanding Quantization in Deep Learning](https://gist.github.com/shekkari1999/70e8213716c1898b80defdd9c14f6237) — INT4/INT8, QAT, weight vs activation quantization
- [ML Training Optimization: FLOPs, Profiling, and Learning Strategies](https://gist.github.com/shekkari1999/8d791fa7d1c098d43285aba4ffa07118) — Chinchilla, I/O bottlenecks, gradient accumulation

**Contact** — [shekkari.akhil@gmail.com](mailto:shekkari.akhil@gmail.com) · [LinkedIn](https://www.linkedin.com/in/akhilshekkari/)
