# Hi, I'm Rishikesh 👋

### 🧠 AI Research Engineer | 🎙️ Voice AI • LLMs • Agentic Systems • ⚡ Efficient Inference

I'm an **AI engineer and researcher with ~10 years of experience**, working across Generative AI, speech synthesis, language models, multimodal systems, and production AI infrastructure.

I enjoy working close to the fundamentals — **implementing architectures from research papers, training and optimizing models, understanding inference at the kernel level, and turning those ideas into production AI systems.**

I **co-founded Dubpro.ai / DeepSync Technologies and currently serve as CTO**, leading AI and engineering across speech synthesis, multilingual AI, generative models, agentic systems, and AI-assisted dubbing technologies.

Alongside my work at Dubpro.ai, I recently collaborated :fire: for six months as an **AI Consultant / Developer with [MyClone.is](https://www.myclone.is) (formerly Rappo), a San Francisco-based company**, where I helped build a real-time **Voice AI digital persona platform** capable of replicating a user's knowledge, conversational style, persona, and voice from their text and voice data.

---

## 🔬 What I Work On & Enjoy Building

I’m always interested in taking on **new technical challenges, research collaborations, and ambitious AI projects**, especially where I can explore new model architectures, understand systems from first principles, and turn research ideas into practical AI products.

### 🤖 LLMs & Model Architectures

* Transformers, **hybrid attention, linear attention, and State Space Models (SSMs)**
* From-scratch PyTorch implementations of modern LLM architectures
* Model loading, **KV caching, decoding, sampling, and generation pipelines**

### ⚡ Training & Inference Optimization

* Fine-tuning, **Reinforcement Learning, RLHF, and post-training alignment**
* PyTorch performance optimization, **Flash Attention / SDPA and GQA**
* CUDA-aware optimization and custom **Triton kernels**
* Optimizing **token throughput, GPU memory usage, latency, and inference performance**

### 🎙️ Voice AI & Generative Audio

* **Text-to-Speech, voice cloning, neural vocoders, and audio codecs**
* Discrete speech/audio representations
* **Diffusion and Flow Matching** based generative models
* Real-time **STT → LLM → TTS** pipelines, Voice AI agents, and telephony systems

### 🧩 Agentic AI, RAG & Memory

* **RAG, vector retrieval, long-term memory, and knowledge systems**
* Multi-agent orchestration and agent workflows
* **MCP, tools, skills, tool calling, and context/state management**
* Real-time AI agents using **LiveKit, Pipecat, and telephony infrastructure**

---

## 🚀 Agentic Projects

### [MyClone](https://github.com/myclone-dev/myclone)

**Production-grade Voice AI + Digital Persona platform**

An open-source version of the platform I worked on at MyClone.is.

Built around **real-time voice conversations, RAG, persistent memory and persona-aware AI**, with a backend involving LiveKit, FastAPI, LlamaIndex, PostgreSQL/pgvector and asynchronous data ingestion.

`Voice AI` · `LiveKit` · `RAG` · `Memory` · `FastAPI` · `pgvector`

---

### [Nexus Code Agent](https://github.com/rishikksh20/nexus-code-agent)

**CLI-first AI coding agent and agent runtime**

A coding agent built around **MCP, custom tools, skills, sub-agents, persistent sessions, context compaction, workspace memory, sandboxed execution and multi-provider LLM support**.

The project is also an exploration of how coding agents can manage long-running context, permissions, delegation, tool execution and repository-level knowledge.

`AI Agents` · `MCP` · `Multi-Agent` · `Context Management` · `Tools` · `Sandboxing`

---

### [Voice AI Agent](https://github.com/rishikksh20/voice-ai-agent-basic)

**Real-time Voice AI + Telephony reference implementation**

A smaller Voice AI system supporting **inbound/outbound Twilio calls, browser WebRTC voice conversations and text chat** using a shared real-time Pipecat pipeline.

`Pipecat` · `Twilio` · `WebRTC` · `STT` · `LLM` · `TTS`

---

## 🧠 LLM & Architecture Implementations

I regularly implement recent model architectures in **bare-minimum PyTorch** to understand the underlying computation rather than treating models as black boxes.

* **[LFM2.5 2.6B](https://github.com/rishikksh20/lfm25-pytorch)** — hybrid convolution/attention LLM, KV-cache optimization and custom Triton inference kernels
* **[Mamba-3](https://github.com/rishikksh20/mamba3-pytorch)** — clean implementation of the latest selective State Space Model architecture
* **[Qwen3.5 0.8B](https://github.com/rishikksh20/qwen3-5-playground)** — hybrid GatedDeltaNet linear attention + GQA implementation
* **[Gemma 3 270M](https://github.com/rishikksh20/gemma3-270m-playground)** — lightweight implementation and model exploration

My focus here is generally on understanding **attention, SSMs, model state, caching, decoding, memory movement and inference performance**.

---

## 🔊 Speech, TTS & Audio Research

Speech synthesis has been one of my longest-running research areas.

Some selected implementations:

* **[Voxtral Codec](https://github.com/rishikksh20/voxtral-codec-pytoch)** — neural audio codec with semantic/acoustic quantization
* **[NU-Wave](https://github.com/rishikksh20/NU-Wave-pytorch)** — diffusion model for neural audio upsampling
* **[iSTFTNet](https://github.com/rishikksh20/iSTFTNet-pytorch)** — lightweight neural vocoder using inverse STFT
* **[VocGAN](https://github.com/rishikksh20/VocGAN)** — real-time neural vocoder and modified adversarial training architecture
* **[AcademiCodec](https://github.com/yangdongchao/AcademiCodec)** — open-source neural audio codec research

My broader work includes **TTS, voice cloning, vocoders, audio codecs, diffusion models, flow matching and real-time speech generation systems**.

---

## 📚 Research Paper Implementations

I also maintain implementations of research papers to study architectures from first principles:

[ViViT](https://github.com/rishikksh20/ViViT-pytorch) ·
[CvT](https://github.com/rishikksh20/convolution-vision-transformers) ·
[LocalViT](https://github.com/rishikksh20/LocalViT-pytorch) ·
[FNet](https://github.com/rishikksh20/FNet-pytorch) ·
[CoaT](https://github.com/rishikksh20/CoaT-pytorch) ·
[SiT](https://github.com/rishikksh20/SiT-pytorch)

These projects span **transformers, convolution-attention hybrids, Fourier token mixing, self-supervised learning, video transformers and generative modeling**.

---

## 🛠️ Tech I Work With

**Models & Research:** PyTorch · Transformers · SSMs · Diffusion · Flow Matching · RL/RLHF · TTS

**Inference:** Triton · CUDA-aware PyTorch · Flash Attention / SDPA · vLLM · KV Cache · Quantization

**Agents:** MCP · RAG · LlamaIndex · LangChain · Multi-Agent Systems · Tool Calling · Long-term Memory

**Voice:** LiveKit · Pipecat · Twilio · Deepgram · AssemblyAI · ElevenLabs · Cartesia

**Backend & Infra:** Python · FastAPI · PostgreSQL · pgvector · Redis · Docker · AWS · GCP

---

## 🤝 Connect

I'm particularly interested in **AI research, LLM systems, Voice AI, intelligent agents, model architecture and efficient inference**.

* **GitHub:** [github.com/rishikksh20](https://github.com/rishikksh20)
* **X / Twitter:** [@ai_rishikesh](https://twitter.com/ai_rishikesh)
* **Email:** [rishikksh20@gmail.com](mailto:rishikksh20@gmail.com)

> I use GitHub both to build production systems and as a research notebook — implementing models from papers, experimenting with new architectures, and understanding AI systems all the way down to their execution details.
