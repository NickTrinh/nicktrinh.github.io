---
layout: page
icon: fas fa-code-branch
order: 1
title: Projects
---

## Selected Systems & Projects

### [Fordham Registration Agent](https://github.com/NickTrinh/registration-agent)
> **3rd Place — Fordham AI Solutions Challenge 2026**

A Chrome Extension (Manifest V3) that embeds a Claude-powered academic advisor inside DegreeWorks:
* **Zero PII on Wire:** Safe-by-construction tokenization replaces student identifiers with placeholders client-side before reaching model APIs.
* **Two-Tier Memory Curator:** Hard facts persist immediately via Sonnet 4.6; implicit user preferences accumulate and promote via Haiku 4.5.
* **Prompt Caching:** System prompt breakpoint saves ~90% input-token costs from turn 2 onwards.
* **Stack:** TypeScript, React 18, Vite, Tailwind CSS, Chrome MV3, IndexedDB, Anthropic SDK.

---

### [Visual Place Recognition & Adaptive Thresholding](https://github.com/NickTrinh/Adaptive-Thresholding-for-Visual-Place-Recognition)
> **IEEE RoboticCC 2025 Publication · Journal Extension for IEEE RA-L**

Open-set visual place recognition under changing environmental conditions:
* **Online Place Discovery:** Discovers and segments reference paths into places without ground truth via Welford incremental statistics and hysteresis.
* **Continuous Adaptive Thresholding:** Derives per-place acceptance boundaries purely from reference data ($\theta_p = \mu_{neg} + k \cdot \sigma_{neg}$ with  = \text{clip}(\text{sep}/2, 1, 2)$).
* **Open-Set Benchmark:** Rejects 92–100% of same-environment distractors on structured benchmarks (Nordland, Bonn, Freiburg, GardensPoint).
* **Stack:** Python, PyTorch (DINOv2 SALAD), NumPy, SciPy.

---

### NPI Graduation Platform & Answer Bot
> **Google Compute Engine (Summer 2026)**

* Gated rollout platform with a 9-phase graduation stepper, real-time bug/critique state verification, and per-phase CLI generation.
* Eliminates fragmented 3-team manual release toil across 12+ graduations per quarter.
* Top-13 of 75 at Google's AI-infra hackathon: built an ADK agent with RPC tool integrations and an Angular drawer, deployed as the Answer Bot on-call assistant.
* **Stack:** Go, gRPC, Cloud Spanner, Protocol Buffers, Angular, ADK.

---

### [TikTok Transcription & Analytics Pipeline](https://github.com/NickTrinh/tiktok-transcription-pipeline)
> **Academic Pipeline — Dr. Li's Lab (DMDA 2026)**

High-throughput distributed ingestion and audio transcription pipeline:
* Batch audio extraction and Whisper speech-to-text with auto-detected FP16 GPU inference and incremental checkpointing.
* Backs empirical analysis accepted to the INFORMS DMDA 2026 workshop.
* **Stack:** Python, PyTorch, OpenAI Whisper, yt-dlp, ffmpeg, pandas.
