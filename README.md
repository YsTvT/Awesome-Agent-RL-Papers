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
| [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) | ICLR 2026 under review| 2025-09 | - | - |
| [SimpleTIR: End-to-End Reinforcement Learning for Multi-Turn Tool-Integrated Reasoning](https://arxiv.org/abs/2509.02479) | arXiv | 2025-09 | [GitHub](https://github.com/ltzheng/SimpleTIR) | ![](https://img.shields.io/github/stars/ltzheng/SimpleTIR?style=social) |
| [Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment](https://arxiv.org/abs/2505.11821) | arXiv | 2025-05 | [GitHub](https://github.com/SiliangZeng/Multi-Turn-RL-Agent) | ![](https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent?style=social) |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | arXiv | 2025-05 | [GitHub](https://github.com/facebookresearch/sweet_rl) | ![](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social) |
| [Group-in-Group Policy Optimization for LLM Agent Training](https://arxiv.org/abs/2505.10978) | arXiv | 2025-05 | [GitHub](https://github.com/langfengQ/verl-agent) | ![](https://img.shields.io/github/stars/langfengQ/verl-agent?style=social) |
| [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516) | COLM 2025 | 2025-05 | [GitHub](https://github.com/PeterGriffinJin/Search-R1) | ![](https://img.shields.io/github/stars/PeterGriffinJin/Search-R1?style=social) |
| [Towards Efficient Online Tuning of VLM Agents via Counterfactual Soft Reinforcement Learning](https://arxiv.org/abs/2505.03792) | ICML 2025 | 2025-05 | [GitHub](https://github.com/langfengQ/CoSo) | ![](https://img.shields.io/github/stars/langfengQ/CoSo?style=social) |
| [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073) | arXiv | 2025-04 | [GitHub](https://github.com/mll-lab-nu/RAGEN) | ![](https://img.shields.io/github/stars/mll-lab-nu/RAGEN?style=social) |
| [NAT: Enhancing Agent Tuning with Negative Samples](https://aclanthology.org/2025.naacl-long.378/) | NAACL 2025 | 2025-04 | [GitHub](https://github.com/Reason-Wang/NAT) | ![](https://img.shields.io/github/stars/Reason-Wang/NAT?style=social) |
| [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.19470) | arXiv | 2025-03 | [GitHub](https://github.com/Agent-RL/ReCall) | ![](https://img.shields.io/github/stars/Agent-RL/ReCall?style=social) |
| [AgentRefine: Enhancing Agent Generalization through Refinement Tuning](https://arxiv.org/abs/2501.01702) | ICLR 2025 | 2025-01 | - | - |
| [Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning](https://arxiv.org/abs/2411.14497) | NeurIPS 2024 | 2024-11 | - | - |
| [ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL](https://arxiv.org/abs/2402.19446) | arXiv | 2024-02 | [GitHub](https://github.com/YifeiZhou02/ArCHer) | ![](https://img.shields.io/github/stars/YifeiZhou02/ArCHer?style=social) |

---

## 🎯 Agent Memory

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [MemGen: Weaving Generative Latent Memory for Self-Evolving Agents](https://arxiv.org/abs/2509.24704v1) | arXiv | 2025-09 | [GitHub](https://github.com/KANABOON1/MemGen) |![](https://img.shields.io/github/stars/KANABOON1/MemGen?style=social) |
| [G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems](https://arxiv.org/abs/2506.07398v2) | arXiv | 2025-06 | [GitHub](https://github.com/bingreeky/GMemory) |![](https://img.shields.io/github/stars/bingreeky/GMemory?style=social) |
| [MIRIX: Multi-Agent Memory System for LLM-Based Agents](https://arxiv.org/abs/2507.07957v1) | arXiv | 2025-07 | [GitHub](https://github.com/Mirix-AI/MIRIX/tree/public_evaluation) |![](https://img.shields.io/github/stars/Mirix-AI/MIRIX?style=social) |


---

## 🎯 Tool Calling

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning](https://arxiv.org/abs/2502.11271) | NAACL 2025 | 2025-02 | [GitHub](https://github.com/octotools/octotools) |![](https://img.shields.io/github/stars/octotools/octotools?style=social) |
| [FROM EXPLORATION TO MASTERY: ENABLING LLMS  TO MASTER TOOLS VIA SELF-DRIVEN INTERACTIONS](https://arxiv.org/abs/2410.08197) | ICLR 2025 | 2025-02 | [GitHub](https://github.com/quchangle1/DRAFT) |![](https://img.shields.io/github/stars/quchangle1/DRAFT?style=social) |
| [StepTool: Enhancing Multi-Step Tool Usage in LLMs via Step-Grained Reinforcement Learning](https://arxiv.org/abs/2410.07745) | CIKM 2025 | 2025-08 | [GitHub](https://github.com/yuyq18/StepTool) |![](https://img.shields.io/github/stars/yuyq18/StepTool?style=social) |
| [AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls](https://arxiv.org/abs/2402.04253) | arXiv | 2024-02 | [GitHub](https://github.com/dyabel/AnyTool) |![](https://img.shields.io/github/stars/dyabel/AnyTool?style=social) |
| [ControlLLM: Augment Language Models with Tools by Searching on Graphs](https://arxiv.org/abs/2310.17796) | ECCV 2024 | 2023-10 | [GitHub](https://github.com/OpenGVLab/ControlLLM) |![](https://img.shields.io/github/stars/OpenGVLab/ControlLLM?style=social) |
| [AGILE: A Novel Reinforcement Learning Framework of LLM Agents](https://arxiv.org/abs/2405.14751) | NeurIPS 2024 | 2024-11 | [GitHub](https://github.com/bytarnish/AGILE) |![](https://img.shields.io/github/stars/bytarnish/AGILE?style=social) |
| [NaviAgent: Bilevel Planning on Tool Dependency Graphs for Function Calling](https://arxiv.org/abs/2405.14751) | arXiv | 2025-06 | - | - |
| [ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings](https://arxiv.org/abs/2305.11554) | NeurIPS 2023 | 2024-01 | [GitHub](https://github.com/Ber666/ToolkenGPT) |![](https://img.shields.io/github/stars/Ber666/ToolkenGPT?style=social) |
| [Toolken+: Improving LLM Tool Usage with Reranking and a Reject Option](https://aclanthology.org/2024.findings-emnlp.345/) | EMNLP 2024 | 2024-10 | - | - |
| [ToRL: Scaling Tool-Integrated RL](https://arxiv.org/abs/2405.14751) | arXiv | 2025-03 | [GitHub](https://github.com/GAIR-NLP/ToRL) |![](https://img.shields.io/github/stars/GAIR-NLP/ToRL?style=social) |
| [Tool-Planner: Task Planning with Clusters across Multiple Tools](https://arxiv.org/abs/2405.14751) | ICLR 2025 | 2025-08 | [GitHub](https://github.com/OceannTwT/Tool-Planner) |![](https://img.shields.io/github/stars/OceannTwT/Tool-Planner?style=social) |
| [ToolDial: Multi-turn Dialogue Generation Method for Tool-Augmented Language Models](https://arxiv.org/abs/2405.14751) | ICLR 2025 | 2025-03 | [GitHub](https://github.com/holi-lab/ToolDial) |![](https://img.shields.io/github/stars/holi-lab/ToolDial?style=social) |
| [MindSearch: Mimicking Human Minds Elicits Deep AI Searcher](https://arxiv.org/abs/2407.20183) | arXiv | 2024-07 | [GitHub](https://github.com/InternLM/MindSearch) | ![](https://img.shields.io/github/stars/InternLM/MindSearch?style=social) |
| [Executable Code Actions Elicit Better LLM Agents](https://openreview.net/forum?id=jJ9BoXAfFa) | ICML 2024 | 2024-05 | [GitHub](https://github.com/xingyaoww/code-act) | ![](https://img.shields.io/github/stars/xingyaoww/code-act?style=social) |
| [TreeRL: LLM Reinforcement Learning with On-Policy Tree Search](https://arxiv.org/abs/2506.11902) | ACL 2025 | 2025-06 | [GitHub](https://github.com/THUDM/TreeRL) | ![](https://img.shields.io/github/stars/THUDM/TreeRL?style=social) |
| [Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution](https://arxiv.org/abs/2505.20286) | arXiv | 2025-05 | [GitHub](https://github.com/CharlesQ9/Alita) | ![](https://img.shields.io/github/stars/CharlesQ9/Alita?style=social) |
| [Agent-as-Tool: A Study on the Hierarchical Decision Making with Reinforcement Learning](https://arxiv.org/abs/2507.01489) | arXiv | 2025-07 | - | - |
| [TOOLVERIFIER: Generalization to New Tools via Self-Verification](https://arxiv.org/abs/2402.14158) | EMNLP 2024 | 2024-02 | [GitHub](https://github.com/facebookresearch/ToolVerifier) | ![](https://img.shields.io/github/stars/facebookresearch/ToolVerifier?style=social) |
| [Learning to Use Tools via Cooperative and Interactive Agents with Large Language Models](https://arxiv.org/abs/2403.03031) | arXiv | 2024-03 | - | - |
| [AutoTIR: Autonomous Tools Integrated Reasoning via Reinforcement Learning](https://arxiv.org/abs/2507.21836) | arXiv | 2025-07 | [GitHub](https://github.com/THUDM/TreeRL) | ![](https://img.shields.io/github/stars/THUDM/TreeRL?style=social) |
| [Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving](https://arxiv.org/abs/2505.07773) | arXiv | 2025-05 | [GitHub](https://github.com/yyht/openrlhf_async_pipline) | ![](https://img.shields.io/github/stars/yyht/openrlhf_async_pipline) |
| [Nemotron-Research-Tool-N1: Exploring Tool-Using Language Models with Reinforced Reasoning](https://arxiv.org/abs/2505.00024) | arXiv | 2025-05 | [GitHub](https://github.com/NVlabs/Tool-N1) | ![](https://img.shields.io/github/stars/NVlabs/Tool-N1?style=social) |
| [GTool: Graph Enhanced Tool Planning with Large Language Model](https://arxiv.org/abs/2508.12725) | arXiv | 2025-08 | - | - |






---

## 🎯 Multi-turn
| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) | ICLR 2026 under review| 2025-09 | - | - |
| [ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL](https://arxiv.org/abs/2402.19446) | arXiv | 2024-02 | [GitHub](https://github.com/YifeiZhou02/ArCHer) | ![](https://img.shields.io/github/stars/YifeiZhou02/ArCHer?style=social) |

---

## 🎯 Agent Evaluation & Benchmark
| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [MCP-AgentBench: Evaluating Real-World Language Agent Performance with MCP-Mediated Tools](https://arxiv.org/abs/2509.09734) | arXiv | 2025-09 | - | - |
| [GitTaskBench: A Benchmark for Code Agents](https://arxiv.org/abs/2508.18993) | arXiv | 2025-08 | [GitHub](https://github.com/QuantaAlpha/GitTaskBench) | ![](https://img.shields.io/github/stars/QuantaAlpha/GitTaskBench?style=social) |
| [MLE-bench: Evaluating Machine Learning Agents on ML Engineering](https://arxiv.org/abs/2410.07095) | ICLR 2025 | 2024-10 | [GitHub](https://github.com/openai/mle-bench) | ![](https://img.shields.io/github/stars/openai/mle-bench?style=social) |
| [WorFBench: Benchmarking Agentic Workflow Generation](https://arxiv.org/abs/2410.07869) | ICLR 2025 | 2024-10 | [GitHub](https://github.com/zjunlp/WorfBench) | ![](https://img.shields.io/github/stars/zjunlp/WorfBench?style=social) |
| [Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470) | CoRR 2024 | 2024-12 | [GitHub](https://github.com/thu-coai/Agent-SafetyBench) | ![](https://img.shields.io/github/stars/thu-coai/Agent-SafetyBench?style=social) |
| [CharacterEval: A Chinese Benchmark for Role-Playing Conversational Agent Evaluation](https://arxiv.org/abs/2401.01275) | ACL 2024 | 2024-01 | [GitHub](https://github.com/morecry/CharacterEval) | ![](https://img.shields.io/github/stars/morecry/CharacterEval?style=social) |
| [AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688) | ICLR 2024 | 2023-08 | [GitHub](https://github.com/THUDM/AgentBench) | ![](https://img.shields.io/github/stars/THUDM/AgentBench?style=social) |

