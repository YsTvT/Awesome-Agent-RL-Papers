# Awesome Agent Papers

A curated collection of research papers on LLM-based agents and agent training methodologies.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Table of Contents
- [Agent Tuning](#agent-tuning)
- [Agent Memory](#agent-memory)
- [Multi-turn ](#multi-turn)
- [Tool Calling](#tool-calling)

---

## 🎯 Agent Tuning

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use, Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804) | COLING 2025 | 2025-01 | [GitHub](https://github.com/xinzhel/LLM-Agent-Survey) | ![](https://img.shields.io/github/stars/xinzhel/LLM-Agent-Survey?style=social) |
| [Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage](https://arxiv.org/abs/2412.15606) | ICLR 2025 | 2024-12 | [GitHub](https://github.com/mat-agent/MAT-Agent) | ![](https://img.shields.io/github/stars/mat-agent/MAT-Agent?style=social) |
| [AgentStudio: A Toolkit for Building General Virtual Agents](https://arxiv.org/abs/2403.17918) | ICLR 2025 | 2024-03 | [GitHub](https://github.com/ltzheng/agent-studio) | ![](https://img.shields.io/github/stars/ltzheng/agent-studio?style=social) |
| [ShortcutsBench: A Large Scale Real-world Benchmark for API-based Agents](https://arxiv.org/abs/2407.00132) | ICLR 2025 | 2024-07 | [GitHub](https://github.com/EachSheep/ShortcutsBench) | ![](https://img.shields.io/github/stars/EachSheep/ShortcutsBench?style=social) |
| [UI-R1: Enhancing Action Prediction of GUI Agents by Reinforcement Learning](https://arxiv.org/abs/2503.21620) | arXiv | 2025-03 | [GitHub](https://github.com/lll6gg/UI-R1) | ![](https://img.shields.io/github/stars/lll6gg/UI-R1?style=social) |
| [GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration](https://arxiv.org/abs/2503.17709) | CVPR 2025 | 2025-03 | [GitHub](https://github.com/921112343/GUI-Xplore) | ![](https://img.shields.io/github/stars/921112343/GUI-Xplore?style=social) |
| [ATLaS: Agent Tuning via Learning Critical Steps](https://arxiv.org/abs/2503.02197) | ACL 2025 | 2025-03 | - | - |
| [WEBRL: Training LLM Web Agents via Self-Evolving Online Curriculum RL](https://arxiv.org/abs/2411.02337) | ICLR 2025 | 2024-11 | [GitHub](https://github.com/THUDM/WebRL) | ![](https://img.shields.io/github/stars/THUDM/WebRL?style=social) |
| [Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents](https://arxiv.org/abs/2408.07199) | arXiv | 2024-08 | [GitHub](https://github.com/sentient-engineering/agent-q) | ![](https://img.shields.io/github/stars/sentient-engineering/agent-q?style=social) |
| [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784) | NeurIPS 2024 | 2024-07 | [GitHub](https://github.com/AI-secure/AgentPoison) | ![](https://img.shields.io/github/stars/AI-secure/AgentPoison?style=social) |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous RL](https://arxiv.org/abs/2406.11896) | NeurIPS 2024 | 2024-06 | [GitHub](https://github.com/DigiRL-agent/digirl) | ![](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social) |
| [Fine-Tuning Large Vision-Language Models as Decision Making Agents via RL](https://arxiv.org/abs/2405.10292) | NeurIPS 2024 | 2024-05 | [GitHub](https://github.com/RL4VLM/RL4VLM) | ![](https://img.shields.io/github/stars/RL4VLM/RL4VLM?style=social) |
| [Cradle: Empowering Foundation Agents Towards General Computer Control](https://arxiv.org/abs/2403.03186) | arXiv | 2024-03 | [GitHub](https://github.com/BAAI-Agents/Cradle) | ![](https://img.shields.io/github/stars/BAAI-Agents/Cradle?style=social) |
| [Agent-FLAN: Designing Data and Methods of Effective Agent Tuning](https://arxiv.org/abs/2403.12881) | ACL Findings 2024 | 2024-03 | [GitHub](https://github.com/InternLM/Agent-FLAN) | ![](https://img.shields.io/github/stars/InternLM/Agent-FLAN?style=social) |
| [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208) | NeurIPS 2024 | 2024-02 | [GitHub](https://github.com/lancopku/agent-backdoor-attacks) | ![](https://img.shields.io/github/stars/lancopku/agent-backdoor-attacks?style=social) |
| [AgentTuning: Enabling Generalized Agent Abilities for LLMs](https://arxiv.org/abs/2310.12823) | ACL Findings 2024 | 2023-10 | [GitHub](https://github.com/THUDM/AgentTuning) | ![](https://img.shields.io/github/stars/THUDM/AgentTuning?style=social) |
| [FireAct: Toward Language Agent Fine-tuning](https://arxiv.org/abs/2310.05915) | arXiv | 2023-10 | [GitHub](https://github.com/anchen1011/FireAct) | ![](https://img.shields.io/github/stars/anchen1011/FireAct?style=social) |
| [EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05 | [GitHub](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) | ![](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social) |
| [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | NeurIPS 2023 | 2023-03 | [GitHub](https://github.com/noahshinn024/reflexion) | ![](https://img.shields.io/github/stars/noahshinn024/reflexion?style=social) |


---

## 🎯 Agent Memory
| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [MemGen: Weaving Generative Latent Memory for Self-Evolving Agents](https://arxiv.org/abs/2509.24704v1) | arXiv | 2025-09 | [GitHub](https://github.com/KANABOON1/MemGen) |![](https://img.shields.io/github/stars/KANABOON1/MemGen?style=social) |
| [G-Memory: Tracing Hierarchical Memory for  Multi-Agent Systems](https://arxiv.org/abs/2506.07398v2) | arXiv | 2025-06 | [GitHub](https://github.com/bingreeky/GMemory) |![](https://img.shields.io/github/stars/bingreeky/GMemory?style=social) |
