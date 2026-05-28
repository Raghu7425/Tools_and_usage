# Tools_and_usage

A curated reference of tools, frameworks, infra, and utilities for building AI agents, voice systems, LLM applications, and scalable AI infrastructure.

---

# Table of Contents

* [Voice Agent Frameworks](#voice-agent-frameworks)
* [LLM Training & Inference Infrastructure](#llm-training--inference-infrastructure)
* [Search & Web Intelligence](#search--web-intelligence)
* [Agent Memory & Vector Search](#agent-memory--vector-search)
* [Speech & Audio Generation](#speech--audio-generation)
* [Agent Development Frameworks](#agent-development-frameworks)
* [Social Media Crawling & Outreach](#social-media-crawling--outreach)
* [Agent Collaboration Platforms](#agent-collaboration-platforms)
* https://github.com/thealgorithms

---

# Voice Agent Frameworks

## 1. Dograh

AI voice agent framework for building conversational voice systems.

* Good for:

  * Real-time voice agents
  * Telephony integrations
  * Speech pipelines
  * Multi-agent voice workflows

GitHub:
[Dograh GitHub](https://github.com/dograh-hq/dograh?utm_source=chatgpt.com)

---

## 2. LiveKit

Real-time communication infrastructure commonly used for voice AI applications.

* Features:

  * WebRTC infrastructure
  * Real-time audio/video
  * Low-latency streaming
  * Agent communication pipelines

Best used for:

* Voice assistants
* Real-time AI calls
* Streaming conversational systems

Official Website:
[LiveKit](https://livekit.io?utm_source=chatgpt.com)

GitHub:
[LiveKit GitHub](https://github.com/livekit/livekit?utm_source=chatgpt.com)

---

# LLM Training & Inference Infrastructure

## 1. DeepSpeed (Microsoft)

Primarily focused on **training and optimization** of massive AI models.

### Key Features

* ZeRO optimization for memory reduction
* Distributed multi-GPU / multi-node training
* CPU & NVMe offloading
* Mixed precision training (FP16/BF16)
* Pipeline parallelism
* Tensor parallelism
* Optimized inference support

### Best Used For

* Pretraining large models
* Fine-tuning LLMs
* RLHF training
* LoRA training
* Training with limited GPU memory
* Scaling across GPU clusters

Official:
[DeepSpeed](https://www.deepspeed.ai?utm_source=chatgpt.com)

GitHub:
[DeepSpeed GitHub](https://github.com/microsoft/DeepSpeed?utm_source=chatgpt.com)

---

## 2. vLLM

Focused on **ultra-fast LLM inference and serving**.

### Key Features

* PagedAttention for efficient KV cache handling
* High-throughput serving
* Low-latency token generation
* OpenAI-compatible API server
* Continuous batching
* Memory-efficient inference

### Best Used For

* Production chatbot serving
* Concurrent multi-user inference
* Long-context generation
* Cost-efficient LLM deployment

Official:
[vLLM](https://vllm.ai?utm_source=chatgpt.com)

GitHub:
[vLLM GitHub](https://github.com/vllm-project/vllm?utm_source=chatgpt.com)

---

# Search & Web Intelligence

## 1. TinyFish

Search + fetch infrastructure optimized for AI agents.

TinyFish uses a real Chromium browser with JavaScript rendering support, removes unnecessary page noise, and returns clean outputs in Markdown, JSON, or HTML.

### Why It Matters

Most web tools:

* Charge per API call
* Return noisy HTML
* Increase token usage significantly

TinyFish:

* Reduces token consumption
* Returns cleaner structured outputs
* Supports modern JS-heavy websites

### Features

* 5 searches per minute (free tier)
* 25 fetches per minute
* Failed fetches do not count
* Structured JSON responses
* Rank-stable results
* Full browser rendering with JS execution

### Works Well With

* OpenClaw
* Hermes Agent
* Claude Code
* Codex
* Cursor

Skill Reference:
[TinyFish Skill Guide](https://github.com/tinyfish-io/tinyfish-cookbook/blob/main/skills/use-tinyfish/SKILL.md?utm_source=chatgpt.com)

GitHub:
[TinyFish GitHub](https://github.com/tinyfish-io/tinyfish-cookbook?utm_source=chatgpt.com)

---

# Agent Memory & Vector Search

## 1. TencentDB for Agent Memory

Useful for:

* Persistent agent memory
* Stateful conversations
* Long-term memory systems
* Session storage

Official:
[TencentDB](https://www.tencentcloud.com/products/tencentdb-for-mongodb?utm_source=chatgpt.com)

---

## 2. TurboVec

Vector search engine optimized for large-scale embeddings and retrieval systems.

### Best Used For

* Semantic search
* RAG pipelines
* Large embedding datasets
* High-performance vector retrieval

GitHub:
[TurboVec GitHub](https://github.com/turbopuffer/turbopuffer?utm_source=chatgpt.com)

---

# Speech & Audio Generation

## 1. SuperTonic

Text-to-speech (TTS) system for generating AI voice outputs.

### Good For

* Voice agents
* AI narration
* Speech synthesis
* Conversational AI

Official:
[Supertonic](https://supertonic.ai?utm_source=chatgpt.com)

---

## 2. VibeVoice (Microsoft)

Model/framework for generating expressive long-form conversational audio.

### Features

* Multi-speaker audio generation
* Long-form podcast-style synthesis
* Expressive conversational speech
* Natural dialogue generation

### Best Used For

* AI podcasts
* Synthetic interviews
* Conversational audio generation
* Storytelling systems

GitHub:
[VibeVoice GitHub](https://github.com/microsoft/VibeVoice?utm_source=chatgpt.com)

---

# Agent Development Frameworks

## 1. Agent Development Kit (ADK)

General toolkit/framework for building AI agents.

Useful for:

* Agent orchestration
* Tool integrations
* Multi-step workflows
* Automation systems

---

# Social Media Crawling & Outreach

## 1. Agent-Reach

Framework/tooling for crawling and interacting across social media platforms.

### Capabilities

* Multi-platform crawling
* Social media automation
* Outreach workflows
* Data extraction

Documentation:
[Agent-Reach Docs](https://github.com/Panniantong/Agent-Reach/blob/main/docs/README_en.md?utm_source=chatgpt.com)

GitHub:
[Agent-Reach GitHub](https://github.com/Panniantong/Agent-Reach?utm_source=chatgpt.com)

---

# Agent Collaboration Platforms

## 1. OpenAgents Workspace

Collaborative operating system for AI agents.

### Description

One shared workspace where multiple AI agents collaborate together.

### Features

* Multi-agent collaboration
* Shared workspace
* Open source
* No account required

Official Website:
[OpenAgents Workspace](https://openagents.com?utm_source=chatgpt.com)

---

# Suggested AI Agent Stack Examples

## Lightweight Voice Agent Stack

* Dograh
* LiveKit
* SuperTonic
* TinyFish
* vLLM

---

## Production LLM Serving Stack

* DeepSpeed (training)
* vLLM (inference)
* TurboVec (RAG/vector search)
* TinyFish (web retrieval)

---

## Autonomous Agent Stack

* Agent Development Kit
* TinyFish
* Agent-Reach
* TencentDB
* OpenAgents Workspace

---

# Notes

## DeepSpeed vs vLLM

| Tool      | Primary Use              |
| --------- | ------------------------ |
| DeepSpeed | Training & optimization  |
| vLLM      | Fast inference & serving |

Use:

* **DeepSpeed** for training large models
* **vLLM** for deploying and serving models efficiently

---

# Future Additions

Potential categories to expand later:

* RAG frameworks
* Multi-agent orchestration
* Open-source copilots
* Browser automation
* Memory architectures
* AI observability
* Evaluation frameworks
* Fine-tuning toolchains
* Speech-to-text systems
* Autonomous coding agents

---

# Personal Notes

This repository is intended as:

* A future reference
* AI stack knowledge base
* Tool discovery collection
* Architecture planning guide
* Rapid prototyping reference

Use this as a starting point whenever building:

* AI agents
* Voice systems
* RAG pipelines
* LLM infrastructure
* Autonomous workflows
* AI products
