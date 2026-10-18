# OmniModel Atlas — Complete Encyclopedia of All AI Models, Parameters, Benchmarks & Inference Systems (1958–2026)

An interactive engineering atlas indexing **historical and frontier AI models (1958–2026)**, their **total and active parameters**, **training compute (FLOPs & tokens)**, **benchmarks**, and the **complete AI inference stack** (runtimes, silicon accelerators, VRAM roofline calculator, and live token streaming simulator).

## Key Features

1. **All AI Models & Metrics Registry (1958–2026)**:
   - Covers **Foundational Era (1958–2011)** (Mark I Perceptron, ELIZA, Hopfield Network, Boltzmann Machine/DBN, LSTM, LeNet-5), **Deep Learning Boom (2012–2016)** (AlexNet, Word2Vec, GAN, VGG-16, GoogLeNet, ResNet-152, AlphaGo), **Transformer Dawn (2017–2021)** (Transformer, GPT-1/2/3, BERT, T5, ViT, CLIP, AlphaFold 2, Switch-C 1.6T, Gopher), **LLM & Generative Era (2022–2023)** (Chinchilla, PaLM, BLOOM, Stable Diffusion, ChatGPT, LLaMA 1/2, GPT-4, Mistral 7B, Mixtral 8x7B, Whisper, Gemini 1.0 Ultra), and **Frontier & Reasoning Era (2024–2026)** (Gemini 4 Argon, Gemini 3.1 Pro, Gemini 2.5 Pro/Flash, GPT-5.4, OpenAI o3/o4-mini/o1, GPT-4.5, GPT-4o, Claude 4.6 Opus, Claude 3.7/3.5 Sonnet, DeepSeek-R1/V3, Llama 4 Behemoth/Maverick/Scout, Llama 3.1 405B/70B/8B, Qwen 3 235B, QwQ-32B, Kimi K2 1T, Grok-3/4, GLM-4.5, MiniMax-01, AlphaFold 3, ESM-3, FLUX.1, Sora 2, Veo 3, π0 VLA).
   - Tracks **Total Parameters**, **Active Parameters per Token (MoE vs Dense)**, **Layers/Heads/Hidden Size**, **Attention Mechanism (MHA, MQA, GQA, MLA, iRoPE, Lightning Attention)**, **Context Window**, **Training Tokens & FLOPs**, **Inference Speed (tok/s)**, **Time to First Token (TTFT ms)**, **VRAM Footprint (FP16 vs INT4)**, **API Pricing**, and **Benchmarks (MMLU, GPQA Diamond, SWE-bench Verified, MATH-500, HumanEval, Chatbot Arena Elo)**.

2. **Interactive VRAM, Roofline Throughput & Cost Calculator + Live Token Race Simulator**:
   - Compute exact **Model Weights VRAM + KV Cache VRAM + Activation Buffer** for any model, precision (`FP32`, `BF16/FP16`, `FP8/INT8`, `INT4/Q4_K_M`, `Q2_K`), context length, batch size, and hardware cluster (`Cerebras WSE-3`, `Groq LPU`, `NVIDIA B200`, `Google TPU Ironwood`, `H200`, `H100`, `MI300X`, `RTX 5090`, `RTX 4090`, `Apple M3 Ultra 512GB`).
   - Run a **Live Token Generation Race** comparing real-time TTFT and token streaming speeds side-by-side.

3. **All Inference Engines, Silicon Accelerators & Cloud Providers**:
   - Detailed architectural profiles of `vLLM`, `SGLang`, `TensorRT-LLM`, `llama.cpp`, `Ollama`, `Apple MLX`, `KTransformers`, `ExLlamaV2`, `Hugging Face TGI`, `ONNX Runtime`, and `ExecuTorch / LiteRT`.

4. **Side-by-Side Comparison Matrix & 68-Year Parameter Scaling Laws**:
   - Compare up to 5 models side-by-side and explore the 10-order-of-magnitude logarithmic parameter scaling timeline from 1958 to 2026.

## Running Locally

Double-click `START_AI_MODELS_ENCYCLOPEDIA.bat` in `d:\Antigravity` or run:

```bash
cd d:\Antigravity\ai-models-encyclopedia
npm run dev
```
