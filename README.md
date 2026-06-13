# Akhil Shekkari

AI Engineer · MS Applied Machine Learning, University of Maryland · 2026

---

I am an AI Engineer and an MS student in Applied Machine Learning at the University of Maryland, College Park. Before UMD, I worked as an AI Engineer at Atrium on a Pfizer R&D project, where I co-authored a **peer-reviewed publication** in *Clinical Trials* (SAGE), and spent three years as a Machine Learning Engineer at Tezo in India.

My work focuses on **LLM inference and post-training**. I build serving systems and training pipelines from scratch: custom Triton kernels, paged KV-cache, speculative decoding, and distributed orchestration with **NVIDIA Dynamo**.

---

**Active projects**

- [`minivllm`](https://github.com/shekkari1999/minivllm) — paged KV cache, continuous batching, and FCFS scheduling for Qwen2.5-7B; 2.6× throughput and 3.5× capacity on H100
- [`triton-kernels`](https://github.com/shekkari1999/triton-kernels) — Triton kernels from vector add through FlashAttention-2; 16.9× speedup at 8K context on H100
- [`coding-agent`](https://github.com/shekkari1999/coding-agent) — CLI coding agent with plan/act loop and self-hosted vLLM inference
- [`reasoning`](https://github.com/shekkari1999/reasoning) — DeepSeek-R1-style post-training for Qwen2.5-3B: SFT + Dr.GRPO on GSM8K and MATH500
- [`Agents`](https://github.com/shekkari1999/Agents) — agent framework with tools, MCP integration, and multi-step reasoning

---

**Writing**

- [GPU Fundamentals & LLM Inference Mental Models](https://gist.github.com/shekkari1999/7a528cb092c21c256068823390ebb510) — roofline model, memory estimation, arithmetic intensity, latency
- [Context in LLMs: What Determines It, What It Costs, and What Actually Works](https://gist.github.com/shekkari1999/d70f2572267c30b99747791bfab00eb9) — architecture, extension methods, agent strategies
- [Serving LLMs with vLLM on RunPod](https://gist.github.com/shekkari1999/3beea10ade914e62a8b41313f06719c0) — PagedAttention, continuous batching, cost benchmarks
- [A Guide to Fine-tuning Methods in LLMs](https://gist.github.com/shekkari1999/cbcfa06f8ff14138188794ce1686dbc6) — LoRA, QLoRA, PEFT, SVD intuition
- [Understanding Quantization in Deep Learning](https://gist.github.com/shekkari1999/70e8213716c1898b80defdd9c14f6237) — INT4/INT8, QAT, weight vs activation quantization
- [ML Training Optimization: FLOPs, Profiling, and Learning Strategies](https://gist.github.com/shekkari1999/8d791fa7d1c098d43285aba4ffa07118) — Chinchilla, I/O bottlenecks, gradient accumulation

**Contact** — [shekkari.akhil@gmail.com](mailto:shekkari.akhil@gmail.com) · [Website](https://shekkari1999.github.io) · [LinkedIn](https://www.linkedin.com/in/akhilshekkari/)
