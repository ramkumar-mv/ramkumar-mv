<h1 align="center">Hi, I'm Ramkumar M V (RK) 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/ramkumar-mv/"><img src="https://img.shields.io/badge/LinkedIn-ramkumar--mv-blue?style=flat-square&logo=linkedin"></a></p>

**Head of AI Research.** I work on **foundation models, Indic speech/TTS, and GPU inference serving** (Triton, vLLM).

On GitHub I publish **measured** work on making models cheaper to train and faster to serve. Every repo ships with
a benchmark script, the hardware it ran on, and the raw numbers. If there's no table, I don't make the claim.

### 🔬 What I'm building

| Repo | What it does | Status |
|---|---|---|
| [**quantbench**](https://github.com/ramkumar-mv/quantbench) | Reproducible LLM quantization benchmarks (FP16 / INT8 / INT4 AWQ·GPTQ / FP8 / NVFP4) on consumer GPUs. Latency, throughput, memory, and quality loss in one harness | 🚧 active |
| **streaming-indic-tts** | Making open TTS models real-time on cheap GPUs: time-to-first-audio, RTF, and quality under quantization | 📋 planned |

### 🎯 Focus areas
- **Inference optimization:** quantization, custom Triton/CUDA kernels, KV-cache tricks, speculative decoding, batching
- **Efficient fine-tuning:** LoRA-family methods and memory-saving tricks
- **Speech efficiency:** streaming TTS/ASR on low-cost hardware
- **Evaluation:** reproducible benchmark harnesses, uncertainty and abstention evals
- **Upstream:** fixes and features for vLLM, llama.cpp, HF Transformers/PEFT, Unsloth

### 🛠️ Stack
`PyTorch` · `Triton` · `CUDA` · `vLLM` · `TensorRT-LLM` · `Triton Inference Server` · `HF Transformers / PEFT` · `llama.cpp` · `Docker`

### 🧭 Background
- B.Tech, E.C.E., SRM Institute of Science and Technology (CGPA 9.58/10)
- AI/ML Associate, IIT Madras · ML Intern, MITACS Globalink (Toronto) · Global Academic Intern, NUS (Singapore)

### 📐 Principles
- Reproducible or it didn't happen: pinned deps, scripts, hardware, raw numbers
- Report quality loss next to every speedup
- Built only on public models and public data
- All experiments run on my own personal workstation (RTX 5070 Ti 16 GB)
