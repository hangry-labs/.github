<p align="center">
  <img src="./assets/hangrylabs_logo_horizontal.webp" alt="Hangry Labs: useful systems, no mystery required" width="100%">
</p>

# 🧪 Hangry Labs

**Local-first tools, baked images, and privacy by default. For humanity and the power of nuggets.**

Hangry Labs builds practical, self-hostable AI systems, automation, dashboards, and creative tools. We package the difficult parts, provide useful interfaces, and explain the real trade-offs so people can run capable software on hardware they control.

Explore [hangrylabs.app](https://hangrylabs.app/) or browse the projects below.

Because sometimes you just want the thing to work.  
Not summon twelve dependency demons and sacrifice your weekend to Python environments.

---

## 🌍 Why Hangry Labs Exists

Modern AI tools are powerful, but many depend on hosted services, hidden infrastructure, disappearing model links, complex setup rituals, or external accounts.

Hangry Labs takes a more independent approach:

- run tools locally or on infrastructure you control
- keep prompts, voices, transcripts, documents, and images private
- provide clear Docker commands and sensible defaults
- include models and dependencies when practical
- offer browser interfaces for people and useful APIs for other systems
- publish honest hardware guidance, measurements, and limitations
- preserve upstream credit, licenses, and links

The ideal first experience should feel like:

```text
docker run ...
```

and then it works.

Maybe not always perfectly. We are still fighting the dependency fires. But that is the direction.

---

## 🧰 Current Projects

What began with local speech tools has grown into a wider collection of AI, operations, and creator software.

| Project | Area | What it offers |
|---|---|---|
| [**KokoroTTS**](https://github.com/hangry-labs/kokoroTTS) | Fast local speech | Multilingual TTS with 173 voices across 11 languages, streaming, SSML workflows, and OpenAI-compatible APIs. |
| [**MeloTTS**](https://github.com/hangry-labs/MeloTTS) | Multilingual speech | A dependable TTS engine with browser UI, API, sentence streaming, and CPU fallback. |
| [**OmniVoiceTTS**](https://github.com/hangry-labs/OmniVoiceTTS) | Voice lab | TTS for 600+ languages with voice design, reference cloning, reusable profiles, and OpenAI-compatible speech routes. |
| [**VoxCPMTTS**](https://github.com/hangry-labs/VoxCPMTTS) | Creative speech | Local VoxCPM2 packaging for multilingual generation, natural voice design, reference cloning, and transcript-guided cloning. |
| [**Qwen3-ASR-STT**](https://github.com/hangry-labs/Qwen3-ASR-STT) | Speech to text | Local transcription, language detection, timestamps, microphone streaming, and OpenAI-compatible clients. |
| [**llama.nodrama**](https://github.com/hangry-labs/llama.nodrama) | LLM operations | A focused diagnostics interface for llama.cpp slots, queues, throughput, KV cache behavior, and request timelines. |
| [**see-through**](https://github.com/hangry-labs/see-through) | Creator tools | Private local anime-character layer decomposition with PSD export, depth tools, selective regeneration, and revision-aware editing. |

Different engines and tools have different strengths. We package them according to what they are actually good at instead of pretending one model should solve everything.

Different nuggets for different disasters.

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
- reproducible AI experiments

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
