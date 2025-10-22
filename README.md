# Awesome Agentic RL Papers

A curated collection of research papers on LLM-based agents and agent training methodologies.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Table of Contents
- [Agent Tuning](#agent-tuning)
- [Agent Memory](#agent-memory)
- [Multi-turn](#Multi-turn)
- [Tool Calling](#tool-calling)
- [Search Agent](#search-agent)
- [Agent Workflow](#agent-workflow)
- [Agent Evaluation & Benchmark](#agent-evaluation--benchmark)
---

## 🎯 Agent Tuning

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) | ICLR 2026 under review | 2025-09 | - | - |
| [SimpleTIR: End-to-End Reinforcement Learning for Multi-Turn Tool-Integrated Reasoning](https://arxiv.org/abs/2509.02479) | arXiv | 2025-09 | [GitHub](https://github.com/ltzheng/SimpleTIR) | ![](https://img.shields.io/github/stars/ltzheng/SimpleTIR?style=social) |
| [Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment](https://arxiv.org/abs/2505.11821) | arXiv | 2025-05 | [GitHub](https://github.com/SiliangZeng/Multi-Turn-RL-Agent) | ![](https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent?style=social) |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | arXiv | 2025-05 | [GitHub](https://github.com/facebookresearch/sweet_rl) | ![](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social) |
| [Group-in-Group Policy Optimization for LLM Agent Training](https://arxiv.org/abs/2505.10978) | arXiv | 2025-05 | [GitHub](https://github.com/langfengQ/verl-agent) | ![](https://img.shields.io/github/stars/langfengQ/verl-agent?style=social) |
| [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516) | COLM 2025 | 2025-05 | [GitHub](https://github.com/PeterGriffinJin/Search-R1) | ![](https://img.shields.io/github/stars/PeterGriffinJin/Search-R1?style=social) |
| [Towards Efficient Online Tuning of VLM Agents via Counterfactual Soft Reinforcement Learning](https://arxiv.org/abs/2505.03792) | ICML 2025 | 2025-05 | [GitHub](https://github.com/langfengQ/CoSo) | ![](https://img.shields.io/github/stars/langfengQ/CoSo?style=social) |
| [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073) | arXiv | 2025-04 | [GitHub](https://github.com/mll-lab-nu/RAGEN) | ![](https://img.shields.io/github/stars/mll-lab-nu/RAGEN?style=social) |
| [NAT: Enhancing Agent Tuning with Negative Samples](https://aclanthology.org/2025.naacl-long.378/) | NAACL 2025 | 2025-04 | [GitHub](https://github.com/Reason-Wang/NAT) | ![](https://img.shields.io/github/stars/Reason-Wang/NAT?style=social) |
| [UI-R1: Enhancing Action Prediction of GUI Agents by Reinforcement Learning](https://arxiv.org/abs/2503.21620) | arXiv | 2025-03 | [GitHub](https://github.com/lll6gg/UI-R1) | ![](https://img.shields.io/github/stars/lll6gg/UI-R1?style=social) |
| [GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration](https://arxiv.org/abs/2503.17709) | CVPR 2025 | 2025-03 | [GitHub](https://github.com/921112343/GUI-Xplore) | ![](https://img.shields.io/github/stars/921112343/GUI-Xplore?style=social) |
| [ATLaS: Agent Tuning via Learning Critical Steps](https://arxiv.org/abs/2503.02197) | ACL 2025 | 2025-03 | - | - |
| [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.19470) | arXiv | 2025-03 | [GitHub](https://github.com/Agent-RL/ReCall) | ![](https://img.shields.io/github/stars/Agent-RL/ReCall?style=social) |
| [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use, Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804) | COLING 2025 | 2025-01 | [GitHub](https://github.com/xinzhel/LLM-Agent-Survey) | ![](https://img.shields.io/github/stars/xinzhel/LLM-Agent-Survey?style=social) |
| [AgentRefine: Enhancing Agent Generalization through Refinement Tuning](https://arxiv.org/abs/2501.01702) | ICLR 2025 | 2025-01 | - | - |
| [Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage](https://arxiv.org/abs/2412.15606) | ICLR 2025 | 2024-12 | [GitHub](https://github.com/mat-agent/MAT-Agent) | ![](https://img.shields.io/github/stars/mat-agent/MAT-Agent?style=social) |
| [WEBRL: Training LLM Web Agents via Self-Evolving Online Curriculum RL](https://arxiv.org/abs/2411.02337) | ICLR 2025 | 2024-11 | [GitHub](https://github.com/THUDM/WebRL) | ![](https://img.shields.io/github/stars/THUDM/WebRL?style=social) |
| [Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning](https://arxiv.org/abs/2411.14497) | NeurIPS 2024 | 2024-11 | - | - |
| [Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents](https://arxiv.org/abs/2408.07199) | arXiv | 2024-08 | [GitHub](https://github.com/sentient-engineering/agent-q) | ![](https://img.shields.io/github/stars/sentient-engineering/agent-q?style=social) |
| [ShortcutsBench: A Large Scale Real-world Benchmark for API-based Agents](https://arxiv.org/abs/2407.00132) | ICLR 2025 | 2024-07 | [GitHub](https://github.com/EachSheep/ShortcutsBench) | ![](https://img.shields.io/github/stars/EachSheep/ShortcutsBench?style=social) |
| [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784) | NeurIPS 2024 | 2024-07 | [GitHub](https://github.com/AI-secure/AgentPoison) | ![](https://img.shields.io/github/stars/AI-secure/AgentPoison?style=social) |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous RL](https://arxiv.org/abs/2406.11896) | NeurIPS 2024 | 2024-06 | [GitHub](https://github.com/DigiRL-agent/digirl) | ![](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social) |
| [Fine-Tuning Large Vision-Language Models as Decision Making Agents via RL](https://arxiv.org/abs/2405.10292) | NeurIPS 2024 | 2024-05 | [GitHub](https://github.com/RL4VLM/RL4VLM) | ![](https://img.shields.io/github/stars/RL4VLM/RL4VLM?style=social) |
| [AgentStudio: A Toolkit for Building General Virtual Agents](https://arxiv.org/abs/2403.17918) | ICLR 2025 | 2024-03 | [GitHub](https://github.com/ltzheng/agent-studio) | ![](https://img.shields.io/github/stars/ltzheng/agent-studio?style=social) |
| [Cradle: Empowering Foundation Agents Towards General Computer Control](https://arxiv.org/abs/2403.03186) | arXiv | 2024-03 | [GitHub](https://github.com/BAAI-Agents/Cradle) | ![](https://img.shields.io/github/stars/BAAI-Agents/Cradle?style=social) |
| [Agent-FLAN: Designing Data and Methods of Effective Agent Tuning](https://arxiv.org/abs/2403.12881) | ACL Findings 2024 | 2024-03 | [GitHub](https://github.com/InternLM/Agent-FLAN) | ![](https://img.shields.io/github/stars/InternLM/Agent-FLAN?style=social) |
| [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208) | NeurIPS 2024 | 2024-02 | [GitHub](https://github.com/lancopku/agent-backdoor-attacks) | ![](https://img.shields.io/github/stars/lancopku/agent-backdoor-attacks?style=social) |
| [ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL](https://arxiv.org/abs/2402.19446) | arXiv | 2024-02 | [GitHub](https://github.com/YifeiZhou02/ArCHer) | ![](https://img.shields.io/github/stars/YifeiZhou02/ArCHer?style=social) |
| [AgentTuning: Enabling Generalized Agent Abilities for LLMs](https://arxiv.org/abs/2310.12823) | ACL Findings 2024 | 2023-10 | [GitHub](https://github.com/THUDM/AgentTuning) | ![](https://img.shields.io/github/stars/THUDM/AgentTuning?style=social) |
| [FireAct: Toward Language Agent Fine-tuning](https://arxiv.org/abs/2310.05915) | arXiv | 2023-10 | [GitHub](https://github.com/anchen1011/FireAct) | ![](https://img.shields.io/github/stars/anchen1011/FireAct?style=social) |
| [EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05 | [GitHub](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) | ![](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social) |
| [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | NeurIPS 2023 | 2023-03 | [GitHub](https://github.com/noahshinn024/reflexion) | ![](https://img.shields.io/github/stars/noahshinn024/reflexion?style=social) |

---

## 🎯 Agent Memory

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension](https://arxiv.org/pdf/2510.05520) | arXiv | 2025-10 |[GitHub](https://github.com/rui9812/CAM)|![](https://img.shields.io/github/stars/rui9812/CAM?style=social)
| [MemGen: Weaving Generative Latent Memory for Self-Evolving Agents](https://arxiv.org/abs/2509.24704v1) | arXiv | 2025-09 | [GitHub](https://github.com/KANABOON1/MemGen) |![](https://img.shields.io/github/stars/KANABOON1/MemGen?style=social) |
| [Mem-α: Learning Memory Construction via Reinforcement Learning](https://arxiv.org/abs/2509.25911v1) | arXiv | 2025-09 | [GitHub](https://github.com/wangyu-ustc/Mem-alpha) |![](https://img.shields.io/github/stars/wangyu-ustc/Mem-alpha?style=social) |
| [Seeing, Listening, Remembering, and Reasoning: A  Multimodal Agent with Long-Term Memory](https://arxiv.org/abs/2508.09736v2) | arXiv | 2025-08 | [GitHub](https://github.com/bytedance-seed/m3-agent) |![](https://img.shields.io/github/stars/bytedance-seed/m3-agent?style=social) |
| [MemAgent: Reshaping Long-Context LLM with  Multi-Conv RL-based Memory Agent](https://arxiv.org/abs/2507.02259v1) | arXiv | 2025-07 | [GitHub](https://github.com/BytedTsinghua-SIA/MemAgent) |![](https://img.shields.io/github/stars/BytedTsinghua-SIA/MemAgent?style=social) |
| [MIRIX: Multi-Agent Memory System for LLM-Based Agents](https://arxiv.org/abs/2507.07957v1) | arXiv | 2025-07 | [GitHub](https://github.com/Mirix-AI/MIRIX/tree/public_evaluation) |![](https://img.shields.io/github/stars/Mirix-AI/MIRIX?style=social) |
| [G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems](https://arxiv.org/abs/2506.07398v2) | arXiv | 2025-06 | [GitHub](https://github.com/bingreeky/GMemory) |![](https://img.shields.io/github/stars/bingreeky/GMemory?style=social) |
| [MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents](https://arxiv.org/abs/2506.15841) | arXiv | 2025-06 | [GitHub](https://github.com/MIT-MI/MEM1) |![](https://img.shields.io/github/stars/MIT-MI/MEM1?style=social) |
| [Memory OS of AI Agent](https://arxiv.org/abs/2506.06326) | arXiv | 2025-06 | [GitHub](https://arxiv.org/abs/2506.06326) |![](https://img.shields.io/github/stars/BAI-LAB/MemoryOS?style=social) |
| [A-Mem: Agentic Memory for LLM Agents](https://arxiv.org/abs/2502.12110) | arXiv | 2025-02 | [GitHub](https://github.com/WujiangXu/A-mem) |![](https://img.shields.io/github/stars/WujiangXu/A-mem?style=social) |
| [InfLLM: Training-Free Long-Context Extrapolation for LLMs with an Efficient Context Memory](https://arxiv.org/abs/2402.04617) | NeurIPS 2024 | 2024-02 | [GitHub](https://github.com/thunlp/InfLLM) |![](https://img.shields.io/github/stars/thunlp/InfLLM?style=social) |
| [RAP: Retrieval-Augmented Planning with Contextual Memory for Multimodal LLM Agents](https://arxiv.org/abs/2402.03610) | NeurIPS 2024 | 2024-02 | [GitHub](https://github.com/PanasonicConnect/rap) |![](https://img.shields.io/github/stars/PanasonicConnect/rap?style=social) |
| [MemGPT:Towards LLMsasOperating Systems](https://arxiv.org/abs/2310.08560) | arXiv | 2023-10 | [GitHub](https://github.com/letta-ai/letta) |![](https://img.shields.io/github/stars/letta-ai/letta?style=social) |
| [Augmenting Language Models with Long-Term Memory](https://arxiv.org/abs/2306.07174) | NeurIPS 2023 | 2023-06 | [GitHub](https://github.com/Victorwz/LongMem) |![](https://img.shields.io/github/stars/Victorwz/LongMem?style=social) |
| [MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://arxiv.org/abs/2305.10250) | AAAI 2024 | 2023-05 | [GitHub](https://github.com/zhongwanjun/MemoryBank-SiliconFriend?tab=readme-ov-file) |![](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend?style=social) |
| [Towards mental time travel: a hierarchical memory for reinforcement learning agents](https://arxiv.org/abs/2105.14039) | NeurIPS 2021 | 2021-05 | - | - |

---

## 🔄 Multi-turn


### Overview and Experience
| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [A Practitioner's Guide to Multi-Turn Agentic Reinforcement Learning](https://arxiv.org/abs/2510.01132v1) | arXiv | 2025-10 | [GitHub](https://github.com/pearls-lab/meow-tea-taro) | ![](https://img.shields.io/github/stars/pearls-lab/meow-tea-taro?style=social) |
| [A Simple "Try Again" Can Elicit Multi-Turn LLM Reasoning](https://arxiv.org/abs/2507.14295v2) | arXiv | 2025-07 | [GitHub](https://github.com/lichengliu03/unary-feedback) | ![](https://img.shields.io/github/stars/lichengliu03/unary-feedback?style=social) |
| [Done Is Better Than Perfect: Unlocking Efficient Reasoning by Structured Multi-Turn Decomposition](https://arxiv.org/abs/2505.19788v2) | arXiv | 2025-05 | - | - |


---


### Environment and Framework


| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [RLFR: EXTENDING REINFORCEMENT LEARNING FOR  LLMS WITH FLOW ENVIRONMENT](https://arxiv.org/abs/2510.10201v1) | arXiv | 2025-10 | [GitHub](https://github.com/Jinghaoleven/RLFR) | ![](https://img.shields.io/github/stars/Jinghaoleven/RLFR?style=social) |
| [Don't Just Fine-tune the Agent, Tune the Environment](https://arxiv.org/abs/2510.10197v1) | arXiv | 2025-10 | [GitHub](https://github.com/inclusionAI) | ![](https://img.shields.io/github/stars/inclusionAI?style=social) |
| [Towards General Agentic Intelligence via Environment Scaling](https://arxiv.org/abs/2509.13311v1) | arXiv | 2025-09 | [GitHub](https://github.com/Alibaba-NLP/DeepResearch) | ![](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=social) |
| [DeepDive: Advancing Deep Search Agents with Knowledge Graphs and Multi-Turn RL](https://arxiv.org/abs/2509.10446v1) | arXiv | 2025-09 | [GitHub](https://github.com/THUDM/DeepDive) | ![](https://img.shields.io/github/stars/THUDM/DeepDive?style=social) |
| [EvoEmo: Towards Evolved Emotional Policies for LLM Agents in Multi-Turn Negotiation](https://arxiv.org/abs/2509.04310v2) | arXiv | 2025-09 | - | - |
| [AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making Through Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2509.08755v1) | arXiv | 2025-09 | [GitHub](https://github.com/woooodyy/AgentGym-RL) | ![](https://img.shields.io/github/stars/woooodyy/AgentGym-RL?style=social) |
| [MUA-RL: Multi-Turn User-Interacting Agent Reinforcement Learning for Agentic Tool Use](https://arxiv.org/abs/2508.18669v1) | arXiv | 2025-08 | [GitHub](https://github.com/zzwkk/MUA-RL) | ![](https://img.shields.io/github/stars/zzwkk/MUA-RL?style=social) |
| [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073v2) | arXiv | 2025-04 | [GitHub](https://github.com/RAGEN-AI/RAGEN) | ![](https://img.shields.io/github/stars/RAGEN-AI/RAGEN?style=social) |
| [ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL](https://arxiv.org/abs/2402.19446) | arXiv | 2024-02 | [GitHub](https://github.com/YifeiZhou02/ArCHer) | ![](https://img.shields.io/github/stars/YifeiZhou02/ArCHer?style=social) |


---


### Policy Optimization


| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) | ICLR 2026 under review | 2025-09 | - | - |
| [Agentic Reinforced Policy Optimization (ARPO)](https://arxiv.org/abs/2507.19849v1) | arXiv | 2025-07 | [GitHub](https://github.com/dongguanting/ARPO) | ![](https://img.shields.io/github/stars/dongguanting/ARPO?style=social) |
| [Group-in-Group Policy Optimization for LLM Agent Training](https://arxiv.org/abs/2505.10978v1) | NeurIPS 2025 | 2025-05 | [GitHub](https://github.com/langfengQ/verl-agent) | ![](https://img.shields.io/github/stars/langfengQ/verl-agent?style=social) |
| [Direct Multi-Turn Preference Optimization for Language Agents](https://arxiv.org/abs/2406.14868v5) | EMNLP 2024 | 2024-06 | [GitHub](https://github.com/swt-user/DMPO) | ![](https://img.shields.io/github/stars/swt-user/DMPO?style=social) |
| [INFORMATION GAIN-BASED POLICY OPTIMIZATION:  A SIMPLE AND EFFECTIVE APPROACH FOR MULTITURN LLM AGENTS](https://arxiv.org/abs/2406.14868v5) | ICLR2026 Under Review | 2024-06 | - | - |



---


### Credit Assignment & Reward


| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [HYBRID REWARD NORMALIZATION FOR PROCESSSUPERVISED NON-VERIFIABLE AGENTIC TASKS](https://arxiv.org/abs/2509.25598v1) | arXiv | 2025-09 | - | - |
| [PARL-MT: Learning to Call Functions in Multi-Turn Conversation with Progress Awareness](https://arxiv.org/abs/2509.23206v2) | arXiv | 2025-09 | - | - |
| [SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution](https://arxiv.org/abs/2505.20732v1) | arXiv | 2025-09 | [[GitHub](https://github.com/WangHanLinHenry/SPA-RL-Agent)](https://github.com/WangHanLinHenry/SPA-RL-Agent) | ![](https://img.shields.io/github/stars/WangHanLinHenry/SPA-RL-Agent?style=social) |
| [Multi-Turn Code Generation Through Single-Step Rewards](https://arxiv.org/abs/2502.20380v2) | arXiv | 2025-09 | [[GitHub](https://github.com/portal-cornell/muCode)](https://github.com/portal-cornell/muCode) | ![](https://img.shields.io/github/stars/portal-cornell/muCode?style=social) |
| [Stabilizing Long-term Multi-turn Reinforcement Learning with Gated Rewards](https://arxiv.org/abs/2508.10548v1) | arXiv | 2025-08 | - | - |
| [Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment](https://arxiv.org/abs/2505.11821v1) | arXiv | 2025-05 | [GitHub](https://github.com/SiliangZeng/Multi-Turn-RL-Agent) | ![](https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent?style=social) |
| [Multi-Turn Reinforcement Learning from Preference Human Feedback](https://arxiv.org/abs/2405.14655v2) | NeurIPS 2024 | 2024-05 | - | - |



---



### Specific Domain


| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Scaling up Multi-Turn Off-Policy RL and Multi-Agent Tree Search for LLM Step-Provers](https://arxiv.org/abs/2509.06493v1) | arXiv | 2025-09 | - | - |
| [Training Long-Context, Multi-Turn Software Engineering Agents with Reinforcement Learning](https://arxiv.org/abs/2508.03501v1) | arXiv | 2025-08 | - | - |
| [Kevin: Multi-Turn RL for Generating CUDA Kernels](https://arxiv.org/abs/2507.11948v1) | arXiv | 2025-07 | - | - |
| [SAMA: Towards Multi-Turn Referential Grounded Video Chat with Large Language Models](https://arxiv.org/abs/2505.18812v1) | NeurIPS 2025 | 2025-05 | [GitHub](https://github.com/sunye23/SAMA) | ![](https://img.shields.io/github/stars/sunye23/SAMA?style=social) |
| [WEBAGENT-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2505.16421v1) | EMNLP 2025 | 2025-05 | [GitHub](https://github.com/weizhepei/WebAgent-R1) | ![](https://img.shields.io/github/stars/weizhepei/WebAgent-R1?style=social) |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478v1) | arXiv | 2025-03 | [GitHub](https://github.com/facebookresearch/sweet_rl) | ![](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social) |
| [Multi-Turn Response Selection with Commonsense-Enhanced Language Models](https://arxiv.org/abs/2407.18479v1) | arXiv | 2024-07 | - | - |


---

## 🎯 Tool Calling

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [StepTool: Enhancing Multi-Step Tool Usage in LLMs via Step-Grained Reinforcement Learning](https://arxiv.org/abs/2410.07745) | CIKM 2025 | 2025-08 | [GitHub](https://github.com/yuyq18/StepTool) |![](https://img.shields.io/github/stars/yuyq18/StepTool?style=social) |
| [Tool-Planner: Task Planning with Clusters across Multiple Tools](https://arxiv.org/abs/2405.14751) | ICLR 2025 | 2025-08 | [GitHub](https://github.com/OceannTwT/Tool-Planner) |![](https://img.shields.io/github/stars/OceannTwT/Tool-Planner?style=social) |
| [GTool: Graph Enhanced Tool Planning with Large Language Model](https://arxiv.org/abs/2508.12725) | arXiv | 2025-08 | - | - |
| [Agent-as-Tool: A Study on the Hierarchical Decision Making with Reinforcement Learning](https://arxiv.org/abs/2507.01489) | arXiv | 2025-07 | - | - |
| [AutoTIR: Autonomous Tools Integrated Reasoning via Reinforcement Learning](https://arxiv.org/abs/2507.21836) | arXiv | 2025-07 | [GitHub](https://github.com/THUDM/TreeRL) | ![](https://img.shields.io/github/stars/THUDM/TreeRL?style=social) |
| [NaviAgent: Bilevel Planning on Tool Dependency Graphs for Function Calling](https://arxiv.org/abs/2506.19500) | arXiv | 2025-06 | - | - |
| [TreeRL: LLM Reinforcement Learning with On-Policy Tree Search](https://arxiv.org/abs/2506.11902) | ACL 2025 | 2025-06 | [GitHub](https://github.com/THUDM/TreeRL) | ![](https://img.shields.io/github/stars/THUDM/TreeRL?style=social) |
| [Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution](https://arxiv.org/abs/2505.20286) | arXiv | 2025-05 | [GitHub](https://github.com/CharlesQ9/Alita) | ![](https://img.shields.io/github/stars/CharlesQ9/Alita?style=social) |
| [Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving](https://arxiv.org/abs/2505.07773) | arXiv | 2025-05 | [GitHub](https://github.com/yyht/openrlhf_async_pipline) | ![](https://img.shields.io/github/stars/yyht/openrlhf_async_pipline) |
| [Nemotron-Research-Tool-N1: Exploring Tool-Using Language Models with Reinforced Reasoning](https://arxiv.org/abs/2505.00024) | arXiv | 2025-05 | [GitHub](https://github.com/NVlabs/Tool-N1) | ![](https://img.shields.io/github/stars/NVlabs/Tool-N1?style=social) |
| [ToRL: Scaling Tool-Integrated RL](https://arxiv.org/abs/2405.14751) | arXiv | 2025-03 | [GitHub](https://github.com/GAIR-NLP/ToRL) |![](https://img.shields.io/github/stars/GAIR-NLP/ToRL?style=social) |
| [ToolDial: Multi-turn Dialogue Generation Method for Tool-Augmented Language Models](https://arxiv.org/abs/2405.14751) | ICLR 2025 | 2025-03 | [GitHub](https://github.com/holi-lab/ToolDial) |![](https://img.shields.io/github/stars/holi-lab/ToolDial?style=social) |
| [OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning](https://arxiv.org/abs/2502.11271) | NAACL 2025 | 2025-02 | [GitHub](https://github.com/octotools/octotools) |![](https://img.shields.io/github/stars/octotools/octotools?style=social) |
| [From Exploration to Mastery: Enabling LLMs to Master Tools via Self-Driven Interactions](https://arxiv.org/abs/2410.08197) | ICLR 2025 | 2025-02 | [GitHub](https://github.com/quchangle1/DRAFT) |![](https://img.shields.io/github/stars/quchangle1/DRAFT?style=social) |
| [AGILE: A Novel Reinforcement Learning Framework of LLM Agents](https://arxiv.org/abs/2405.14751) | NeurIPS 2024 | 2024-11 | [GitHub](https://github.com/bytarnish/AGILE) |![](https://img.shields.io/github/stars/bytarnish/AGILE?style=social) |
| [Toolken+: Improving LLM Tool Usage with Reranking and a Reject Option](https://aclanthology.org/2024.findings-emnlp.345/) | EMNLP 2024 | 2024-10 | - | - |
| [MindSearch: Mimicking Human Minds Elicits Deep AI Searcher](https://arxiv.org/abs/2407.20183) | arXiv | 2024-07 | [GitHub](https://github.com/InternLM/MindSearch) | ![](https://img.shields.io/github/stars/InternLM/MindSearch?style=social) |
| [Executable Code Actions Elicit Better LLM Agents](https://openreview.net/forum?id=jJ9BoXAfFa) | ICML 2024 | 2024-05 | [GitHub](https://github.com/xingyaoww/code-act) | ![](https://img.shields.io/github/stars/xingyaoww/code-act?style=social) |
| [Learning to Use Tools via Cooperative and Interactive Agents with Large Language Models](https://arxiv.org/abs/2403.03031) | arXiv | 2024-03 | - | - |
| [AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls](https://arxiv.org/abs/2402.04253) | arXiv | 2024-02 | [GitHub](https://github.com/dyabel/AnyTool) |![](https://img.shields.io/github/stars/dyabel/AnyTool?style=social) |
| [TOOLVERIFIER: Generalization to New Tools via Self-Verification](https://arxiv.org/abs/2402.14158) | EMNLP 2024 | 2024-02 | [GitHub](https://github.com/facebookresearch/ToolVerifier) | ![](https://img.shields.io/github/stars/facebookresearch/ToolVerifier?style=social) |
| [ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings](https://arxiv.org/abs/2305.11554) | NeurIPS 2023 | 2024-01 | [GitHub](https://github.com/Ber666/ToolkenGPT) |![](https://img.shields.io/github/stars/Ber666/ToolkenGPT?style=social) |
| [ControlLLM: Augment Language Models with Tools by Searching on Graphs](https://arxiv.org/abs/2310.17796) | ECCV 2024 | 2023-10 | [GitHub](https://github.com/OpenGVLab/ControlLLM) |![](https://img.shields.io/github/stars/OpenGVLab/ControlLLM?style=social) |


---
## 🎯 Search Agent
| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents](https://arxiv.org/abs/2509.09265) | ICLR 2026 under review | 2025-09 | - | - |
| [SimpleTIR: End-to-End Reinforcement Learning for Multi-Turn Tool-Integrated Reasoning](https://arxiv.org/abs/2509.02479) | arXiv | 2025-09 | [GitHub](https://github.com/ltzheng/SimpleTIR) | ![](https://img.shields.io/github/stars/ltzheng/SimpleTIR?style=social) |
| [Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment](https://arxiv.org/abs/2505.11821) | arXiv | 2025-05 | [GitHub](https://github.com/SiliangZeng/Multi-Turn-RL-Agent) | ![](https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent?style=social) |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | arXiv | 2025-05 | [GitHub](https://github.com/facebookresearch/sweet_rl) | ![](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social) |
| [Group-in-Group Policy Optimization for LLM Agent Training](https://arxiv.org/abs/2505.10978) | arXiv | 2025-05 | [GitHub](https://github.com/langfengQ/verl-agent) | ![](https://img.shields.io/github/stars/langfengQ/verl-agent?style=social) |
| [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516) | COLM 2025 | 2025-05 | [GitHub](https://github.com/PeterGriffinJin/Search-R1) | ![](https://img.shields.io/github/stars/PeterGriffinJin/Search-R1?style=social) |
| [Towards Efficient Online Tuning of VLM Agents via Counterfactual Soft Reinforcement Learning](https://arxiv.org/abs/2505.03792) | ICML 2025 | 2025-05 | [GitHub](https://github.com/langfengQ/CoSo) | ![](https://img.shields.io/github/stars/langfengQ/CoSo?style=social) |
| [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073) | arXiv | 2025-04 | [GitHub](https://github.com/mll-lab-nu/RAGEN) | ![](https://img.shields.io/github/stars/mll-lab-nu/RAGEN?style=social) |
| [NAT: Enhancing Agent Tuning with Negative Samples](https://aclanthology.org/2025.naacl-long.378/) | NAACL 2025 | 2025-04 | [GitHub](https://github.com/Reason-Wang/NAT) | ![](https://img.shields.io/github/stars/Reason-Wang/NAT?style=social) |
| [UI-R1: Enhancing Action Prediction of GUI Agents by Reinforcement Learning](https://arxiv.org/abs/2503.21620) | arXiv | 2025-03 | [GitHub](https://github.com/lll6gg/UI-R1) | ![](https://img.shields.io/github/stars/lll6gg/UI-R1?style=social) |
| [GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration](https://arxiv.org/abs/2503.17709) | CVPR 2025 | 2025-03 | [GitHub](https://github.com/921112343/GUI-Xplore) | ![](https://img.shields.io/github/stars/921112343/GUI-Xplore?style=social) |
| [ATLaS: Agent Tuning via Learning Critical Steps](https://arxiv.org/abs/2503.02197) | ACL 2025 | 2025-03 | - | - |
| [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.19470) | arXiv | 2025-03 | [GitHub](https://github.com/Agent-RL/ReCall) | ![](https://img.shields.io/github/stars/Agent-RL/ReCall?style=social) |
| [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use, Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804) | COLING 2025 | 2025-01 | [GitHub](https://github.com/xinzhel/LLM-Agent-Survey) | ![](https://img.shields.io/github/stars/xinzhel/LLM-Agent-Survey?style=social) |
| [AgentRefine: Enhancing Agent Generalization through Refinement Tuning](https://arxiv.org/abs/2501.01702) | ICLR 2025 | 2025-01 | - | - |
| [WebWalker: Benchmarking LLMs in Web Traversal](https://arxiv.org/abs/2501.07572) | ACL 2025 | 2025-01 | - | - |
| [Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage](https://arxiv.org/abs/2412.15606) | ICLR 2025 | 2024-12 | [GitHub](https://github.com/mat-agent/MAT-Agent) | ![](https://img.shields.io/github/stars/mat-agent/MAT-Agent?style=social) |
| [WEBRL: Training LLM Web Agents via Self-Evolving Online Curriculum RL](https://arxiv.org/abs/2411.02337) | ICLR 2025 | 2024-11 | [GitHub](https://github.com/THUDM/WebRL) | ![](https://img.shields.io/github/stars/THUDM/WebRL?style=social) |
| [Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning](https://arxiv.org/abs/2411.14497) | NeurIPS 2024 | 2024-11 | - | - |
| [Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents](https://arxiv.org/abs/2408.07199) | arXiv | 2024-08 | [GitHub](https://github.com/sentient-engineering/agent-q) | ![](https://img.shields.io/github/stars/sentient-engineering/agent-q?style=social) |
| [ShortcutsBench: A Large Scale Real-world Benchmark for API-based Agents](https://arxiv.org/abs/2407.00132) | ICLR 2025 | 2024-07 | [GitHub](https://github.com/EachSheep/ShortcutsBench) | ![](https://img.shields.io/github/stars/EachSheep/ShortcutsBench?style=social) |
| [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784) | NeurIPS 2024 | 2024-07 | [GitHub](https://github.com/AI-secure/AgentPoison) | ![](https://img.shields.io/github/stars/AI-secure/AgentPoison?style=social) |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous RL](https://arxiv.org/abs/2406.11896) | NeurIPS 2024 | 2024-06 | [GitHub](https://github.com/DigiRL-agent/digirl) | ![](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social) |
| [Fine-Tuning Large Vision-Language Models as Decision Making Agents via RL](https://arxiv.org/abs/2405.10292) | NeurIPS 2024 | 2024-05 | [GitHub](https://github.com/RL4VLM/RL4VLM) | ![](https://img.shields.io/github/stars/RL4VLM/RL4VLM?style=social) |
| [AgentStudio: A Toolkit for Building General Virtual Agents](https://arxiv.org/abs/2403.17918) | ICLR 2025 | 2024-03 | [GitHub](https://github.com/ltzheng/agent-studio) | ![](https://img.shields.io/github/stars/ltzheng/agent-studio?style=social) |
| [Cradle: Empowering Foundation Agents Towards General Computer Control](https://arxiv.org/abs/2403.03186) | arXiv | 2024-03 | [GitHub](https://github.com/BAAI-Agents/Cradle) | ![](https://img.shields.io/github/stars/BAAI-Agents/Cradle?style=social) |
| [Agent-FLAN: Designing Data and Methods of Effective Agent Tuning](https://arxiv.org/abs/2403.12881) | ACL Findings 2024 | 2024-03 | [GitHub](https://github.com/InternLM/Agent-FLAN) | ![](https://img.shields.io/github/stars/InternLM/Agent-FLAN?style=social) |
| [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208) | NeurIPS 2024 | 2024-02 | [GitHub](https://github.com/lancopku/agent-backdoor-attacks) | ![](https://img.shields.io/github/stars/lancopku/agent-backdoor-attacks?style=social) |
| [ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL](https://arxiv.org/abs/2402.19446) | arXiv | 2024-02 | [GitHub](https://github.com/YifeiZhou02/ArCHer) | ![](https://img.shields.io/github/stars/YifeiZhou02/ArCHer?style=social) |
| [WebDancer: Towards Autonomous Information Seeking Agency](https://arxiv.org/abs/2505.22648) | arXiv | 2025-05 | - | - |
| [WebSailor: Navigating Super-human Reasoning for Web Agent](https://arxiv.org/abs/2507.02592) | arXiv | 2025-07 | - | - |
| [WebShaper: Agentically Data Synthesizing via Information-Seeking Formalization](https://arxiv.org/abs/2507.15061) | arXiv | 2025-07 | - | - |
| [AgentTuning: Enabling Generalized Agent Abilities for LLMs](https://arxiv.org/abs/2310.12823) | ACL Findings 2024 | 2023-10 | [GitHub](https://github.com/THUDM/AgentTuning) | ![](https://img.shields.io/github/stars/THUDM/AgentTuning?style=social) |
| [FireAct: Toward Language Agent Fine-tuning](https://arxiv.org/abs/2310.05915) | arXiv | 2023-10 | [GitHub](https://github.com/anchen1011/FireAct) | ![](https://img.shields.io/github/stars/anchen1011/FireAct?style=social) |
| [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13834) | NeurIPS 2023 | 2023-07 | [GitHub](https://github.com/web-arena/WebArena) | ![](https://img.shields.io/github/stars/web-arena/WebArena?style=social) |
| [GAIA: a benchmark for General AI Assistants](https://arxiv.org/abs/2311.15398) | NeurIPS 2023 | 2023-07 | [GitHub](https://github.com/ServiceNow/GAIA) | ![](https://img.shields.io/github/stars/ServiceNow/GAIA?style=social) |
| [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | NeurIPS 2023 | 2023-03 | [GitHub](https://github.com/noahshinn024/reflexion) | ![](https://img.shields.io/github/stars/noahshinn024/reflexion?style=social) |
| [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) | ICLR 2023 | 2022-10 | [GitHub](https://github.com/ysymyth/reasoning-with-acting) | ![](https://img.shields.io/github/stars/ysymyth/reasoning-with-acting?style=social) |
| [ToolFormer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) | NeurIPS 2023 | 2022-07 | [GitHub](https://github.com/microsoft/ToolFormer) | ![](https://img.shields.io/github/stars/microsoft/ToolFormer?style=social) |
| [WebGPT: Browser-assisted question-answering with human feedback](https://arxiv.org/abs/2112.09332) | arXiv | 2021-12 | - | - |
--


## 🎯 Agent Workflow

| Title | Venue | Date | Code | Stars |
|-------|-------|------|------|-------|
| [Agentdistill: training-free agent distillation withgeneralizable mcp boxes](https://arxiv.org/abs/2506.14728) | arXiv | 2025-06 | - | - |
| [Get Experience from Practice: LLM Agents with Record & Replay](https://arxiv.org/abs/2505.17716) | arXiv  | 2025-05 | - | - |
| [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762) | ICLR 2025 | 2024-10 | [GitHub](https://github.com/FoundationAgents/AFlow) | ![](https://img.shields.io/github/stars/FoundationAgents/AFlow?style=social) |
| [Agent Workflow Memory](https://arxiv.org/abs/2409.07429) | arXiv | 2024-09 | [GitHub](https://github.com/zorazrw/agent-workflow-memory) | ![](https://img.shields.io/github/stars/zorazrw/agent-workflow-memory?style=social) |
| [Agent KB: Leveraging Cross-Domain Experience for Agentic Problem Solving](https://arxiv.org/abs/2507.06229) | ICML 2025 | 2024-07 | [GitHub](https://github.com/OPPO-PersonalAI/Agent-KB) | ![](https://img.shields.io/github/stars/OPPO-PersonalAI/Agent-KB?style=social) |


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

