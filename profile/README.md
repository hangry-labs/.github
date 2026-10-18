<p align="center">
  <img src="./assets/hangrylabs_logo_horizontal.webp" alt="Hangry Labs: useful systems, no mystery required" width="100%">
</p>

<p align="center">
  <strong>English</strong> ·
  <a href="README.nb.md">Norsk bokmål</a> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.zh.md">简体中文</a> ·
  <a href="README.es.md">Español</a>
</p>

# 🧪 Hangry Labs

**Local-first AI and open software, packaged to run on hardware you control. For humanity and the power of nuggets.**

Hangry Labs builds practical, self-hostable AI systems, automation, dashboards, standards, and creative tools. We package the difficult parts, provide useful interfaces, and explain the real trade-offs so capable software is easier to run, understand, connect, and preserve.

Explore the [Hangry Labs software catalog](https://hangrylabs.app/software) for product guides, real examples, and installation help.

Because sometimes you just want the thing to work.  
Not summon twelve dependency demons and sacrifice your weekend to Python environments.

---

## ⚡ Pick a Tool and Get Running

The [software catalog](https://hangrylabs.app/software) helps you compare the current applications and hear real voice examples before downloading anything.

For the Docker-based speech tools, each installation guide asks six short questions about your operating system, hardware, download size, release track, image registry, and network access. It then produces one exact command and explains every step in plain language. Your answers stay in your browser and are not submitted to the server.

Choose a project, open **Installation help**, and let the wizard handle the command-building side quest.

---

## 🌍 Why Hangry Labs Exists

Modern AI tools are powerful, but many depend on hosted services, hidden infrastructure, disappearing model links, complex setup rituals, or external accounts.

Hangry Labs takes a more independent approach:

- run tools locally or on infrastructure you control
- keep prompts, voices, transcripts, documents, and images private
- provide clear Docker commands and sensible defaults
- include models and dependencies when practical
- offer browser interfaces for people and documented APIs for applications
- publish honest hardware guidance, measurements, and limitations
- preserve upstream credit, licenses, and links

The ideal first experience should feel like:

```text
docker run ...
```

and then it works.

Maybe not always perfectly. We are still fighting the dependency fires. But that is the direction.

---

## 🧰 Applications

What began with local speech tools has grown into a wider collection of AI, operations, and creator software.

| Project | Area | What it offers |
|---|---|---|
| [**KokoroTTS**](https://github.com/hangry-labs/kokoroTTS) | Fast local speech | 173 voices across 11 languages, five independently managed model packs, streaming, SSML dialogue, native and OpenAI-compatible APIs, and opt-in MCP tools. |
| [**MeloTTS**](https://github.com/hangry-labs/MeloTTS) | Multilingual speech | Eight models across six languages, browser model management, six output formats, sentence-streamed MP3 and PCM, and native and OpenAI-compatible APIs. |
| [**OmniVoiceTTS**](https://github.com/hangry-labs/OmniVoiceTTS) | Voice lab | Speech for 600+ languages with voice design, microphone and reference cloning, reusable profiles, SSML-H dialogue, streaming, and OpenAI-compatible APIs. |
| [**VoxCPMTTS**](https://github.com/hangry-labs/VoxCPMTTS) | Creative speech | Nano-vLLM-powered generation across 30 languages, natural voice design, reference and transcript-guided cloning, reusable profiles, progressive streaming, and HTTP APIs. |
| [**Qwen3-ASR-STT**](https://github.com/hangry-labs/Qwen3-ASR-STT) | Speech to text | Local 30-language transcription, live microphone sessions, timestamps and subtitles, OpenAI-compatible clients, and opt-in MCP transcription for files and URLs. |
| [**llama.nodrama**](https://github.com/hangry-labs/llama.nodrama) | LLM operations | A lightweight dashboard for llama.cpp slots, queues, throughput, KV cache behavior, request timelines, and the operational details hidden behind a local LLM endpoint. |
| [**see-through**](https://github.com/hangry-labs/see-through) | Creator tools | Private local anime-character layer decomposition with layered PSD export, interactive depth previews, manual ordering, selective regeneration, and source-detail recovery. |

Different engines and tools have different strengths. We package them according to what they are actually good at instead of pretending one model should solve everything.

Different nuggets for different disasters.

### Standards and building blocks

| Project | Role | Current focus |
|---|---|---|
| [**Faster Qwen3-TTS**](https://github.com/hangry-labs/faster-qwen3-tts-studio) | Performance runtime | Real-time streaming and non-streaming Qwen3-TTS inference with CUDA Graph acceleration, an OpenAI-compatible server, and an experimental GGML backend for CUDA and Apple Silicon. |
| [**SSML-H Specification**](https://github.com/hangry-labs/ssml-h-spec) | Speech markup | The normative home of the independent Hangry Labs extension profile for W3C SSML 1.1, including dynamic voice declarations and per-turn direction. |
| [**SSML-H Tools**](https://github.com/hangry-labs/ssml-h-tools) | Reference library | An engine-neutral Python parser, validator, and builder that compiles SSML and SSML-H into immutable synthesis plans. |

---

## 🛠️ How We Build

### Local-first and private by default

Your data should stay close. Hangry Labs projects aim to work on your machine or server without sending sensitive inputs to someone else's cloud.

### Baked when practical

Full Docker images can include model assets, runtime dependencies, and the application itself. When a fully baked image would be impractical, projects can provide a smaller image backed by a stable persistent data volume.

The goal is reliability, not winning a contest for the smallest image. A larger image that still works next year is often more useful than a tiny image that breaks when a package changes or a model link disappears.

### Open interfaces

People should have a clear browser interface. Applications and automations should have documented HTTP APIs, useful status endpoints, and predictable behavior.

Where OpenAI-compatible APIs make sense, we use them as a practical compatibility baseline while keeping useful product-specific capabilities available.

### Honest limits

Fast models can have narrower capabilities. Powerful models can need more memory and patience. Benchmarks should name their hardware and settings, and compatibility guidance should be clear about what was measured.

No magic smoke. Only mildly dramatic engineering reality.

### Respect for upstream work

Many Hangry Labs projects build on excellent open-source research and software. We keep upstream attribution and licenses visible, explain what came from upstream, and document what Hangry Labs adds around packaging, interfaces, deployment, and validation.

---

## 🚀 Long-Term Direction

Hangry Labs is still a lab for useful side quests. The broader direction includes local-first tools for:

- AI companions and voice interfaces
- memory and knowledge systems
- self-hosted dashboards
- private automation
- creator tools
- game and streaming utilities
- model serving and observability
- speech markup and interoperability
- fast, reproducible AI inference

The aim is a collection of tools that people can run, understand, modify, connect, and preserve.

Not everything needs to be a cloud subscription. Some things should simply belong to the people using them.

---

## 🧃 For Humanity and the Power of Nuggets

We build for people who want to run things themselves.

For builders.<br>
For creators.<br>
For privacy.<br>
For weird experiments.<br>
For the small fixes that become giant projects.<br>
For humanity.

And, naturally, for the power of nuggets.

Check the pinned repositories below for the projects currently receiving the most attention.
