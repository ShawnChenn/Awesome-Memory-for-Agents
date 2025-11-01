# Awesome-Memory-for-Agents

## Table of Contents

- [Awesome-Memory-for-Agents](#awesome-memory-for-agents)
    - [Overview](#overview)
    - [Paper List](#paper-list)
        - [Application](#application)
            - [Personalization](#personalization)
            - [Learning from Experience](#learning-from-experience)
            - [Long-horizon Agentic Task](#long-horizon-agentic-task)
        - [Survey](#survey)
        - [Benchmark](#benchmark)
        - [Product \& Project](#product--project)

## Overview

This repository provides a curated list of papers on agent memory, structured by a core taxonomy. We first divide agent memory based on its persistence:

- **Short-Term Memory:** Transient information managed within the context window for a single task;
- **Long-Term Memory:** Persistent information stored externally across tasks.

Within *Long-Term Memory*, we further distinguish based on its reliance on task success/failure for curation:

- **Memory (for Personalization)** denotes information without reference to task success/failure;
- **Experience (for Learning)** involves knowledge explicitly curated through task success/failure.

This taxonomy maps directly to the three primary application scenarios that organize the papers in this repository:

| Application               | Memory Content                                               | Description                                          |
| :------------------------ | :----------------------------------------------------------- | :--------------------------------------------------- |
| Personalization           | User profiles, interaction history, facts, etc.              | Continuous personalized interaction                  |
| Learning from Experience  | Trajectories, success/failure lessons, reusable skills, etc. | Cross-task experience accumulation & transfer        |
| Long-horizon Agentic Task | Intermediate steps, reasoning traces                         | Context management within a single long-horizon task |

## Paper List

### Application

#### Personalization

| Date | Title | Paper |
|:------:|:------|:------:|
| 2025-10 | Improving Code Localization with Repository Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01003) |
| 2025-10 | Mnemosyne: An Unsupervised, Human-Inspired Long-Term Memory Architecture for Edge-Based LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08601) |
| 2025-10 | AssoMem: Scalable Memory QA with Multi-Signal Associative Retrieval | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.10397) |
| 2025-09 | TOM-SWE: User Mental Modeling For Software Engineering Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=A4koL4Zqam) |
| 2025-09 | MEM-$\alpha$: LEARNING MEMORY CONSTRUCTION VIA REINFORCEMENT LEARNING | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=dm42omwep1) |
| 2025-09 | PISA: A Pragmatic Psych-Inspired Unified Memory System for Enhanced AI Agency | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=l82wkoRQ3l) |
| 2025-09 | Look Back to Reason Forward: Revisitable Memory for Long-Context LLM Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=1cymflI2Lh) |
| 2025-09 | Memory-T1: Reinforcement Learning for Temporal Reasoning in Multi-session Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=vQf2YR2Kpd) |
| 2025-09 | MIRA: Memory-Integrated Reinforcement Learning Agent  with Limited LLM Guidance | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=oWagByDNPc) |
| 2025-09 | EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=sooLoD9VSf) |
| 2025-09 | REMem: Reasoning with Episodic Memory in Language Agent | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=fugnQxbvMm) |
| 2025-09 | Adaptive Friend Agent: Personalized Multi-User Memory for Conversational AI | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=wKTwm7ZzDK) |
| 2025-08 | Orchid: Orchestrating Context Across Creative Workflows with Generative AI | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.19517) |
| 2025-07 | MemOS: A Memory OS for AI System | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.03724) |
| 2025-06 | PersonaAgent: When Large Language Model Agents Meet Personalization at Test Time | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.06254) |
| 2025-06 | SynthesizeMe! Inducing Persona-Guided Prompts for Personalized Reward Models in LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.05598) |
| 2025-02 | A-MEM: Agentic Memory for LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.12110) |
| 2025-01 | Wormhole Memory: A Rubik's Cube for Cross-Dialogue Retrieval | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.14846) |
| 2024-12 | On the Structural Memory of LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.15266) |
| 2024-07 | MemoCRS: Memory-enhanced Sequential Conversational Recommender Systems with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.04960) |
| 2024-01 | From llm to conversational agent: A memory enhanced architecture with fine-tuning of large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2401.02777) |
| 2023-08 | Memochat: Tuning llms to use memos for consistent long-range open-domain conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.08239) |
| 2023-06 | Chatdb: Augmenting llms with databases as their symbolic memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2306.03901) |
| 2023-05 | MemoryBank: Enhancing large language models with long-term memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.10250) |
| 2023-04 | Unleashing infinite-length input capacity for large-scale language models with self-controlled memory system | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2304.13343) |

#### Learn from Experience

| Date | Title | Paper |
|:------:|:------|:------:|
| 2025-10 | Dyna-Mind: Learning to Simulate from Experience for Better AI Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.09577) |
| 2025-10 | LEGOMem: Modular Procedural Memory for Multi-agent LLM Systems for Workflow Automation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.04851) |
| 2025-10 | TokMem: Tokenized Procedural Memory for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.00444) |
| 2025-09 | WebOperator: Action-Aware Tree Search for Autonomous Agents in Web Environment | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=vnEuxLVFmN) |
| 2025-09 | Exploratory Memory-Augmented LLM Agent via Hybrid On- and Off-Policy Optimization | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=UOzxviKVFO) |
| 2025-09 | Automated Stateful Specialization for Adaptive Agent Systems | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=UESTP6dR1K) |
| 2025-09 | Alita-G: Self-Evolving Generative Agent for Agent Generation | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=xf2JC4531b) |
| 2025-09 | SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=OuW3gCJRBK) |
| 2025-09 | BMAS: A Brain-Inspired Multi-Agent System with PFC-Guided Task Coordination and Hippocampus-Neocortex Dual Memory for Scalable Multi-Step Reasoning | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=YqFLsI44vN) |
| 2025-09 | Scaling Agent Learning via Experience Synthesis | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=cf7qpBwttr) |
| 2025-09 | Xolver: Generalist Reasoning and Problem Solving through Federated Multi-Agent Dynamics and Holistic Experience Learning | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=xXhgzwwQ42) |
| 2025-09 | MetaEvo: A Meta-Optimization Framework for Experience-Driven Agent Evolution | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=1YcMHVY9cl) |
| 2025-09 | ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=jL7fwchScm) |
| 2025-09 | Agent KB: Leveraging Cross-Domain Experience for Agentic Problem Solving | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=QCLXVOMkl4) |
| 2025-09 | Agentic Context Engineering: Learning Comprehensive Contexts for Self-Improving Language Models | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=eC4ygDs02R) |
| 2025-09 | ArcMemo: Abstract Reasoning Composition with Lifelong LLM Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.04439) |
| 2025-08 | Memento: Fine-tuning LLM Agents without Fine-tuning LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.16153) |
| 2025-08 | SE-Agent: Self-Evolution Trajectory Optimization in Multi-Step Reasoning with LLM-Based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.02085) |
| 2025-07 | SWE-Exp: Experience-Driven Software Issue Resolution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.23361) |
| 2025-06 | Cost-Efficient Serving of LLM Agents via Test-Time Plan Caching | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.14852) |
| 2025-06 | MAPLE: Multi-Agent Adaptive Planning with Long-Term Memory for Table Reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.05813) |
| 2025-05 | ML-Agent: Reinforcing LLM Agents for Autonomous Machine Learning Engineering | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.23723) |
| 2025-05 | How Memory Management Impacts LLM Agents: An Empirical Study of Experience-Following Behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.16067) |
| 2025-05 | Efficiently enhancing general agents with hierarchical-categorical memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.22006) |
| 2025-04 | SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.07079) |
| 2025-04 | Inducing Programmatic Skills for Agentic Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.06821) |
| 2025-04 | Memorization and knowledge injection in gated llms | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.21239) |
| 2025-03 | Mars: Memory-enhanced agents with reflective self-improvement | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.19271) |
| 2024-09 | Agent workflow memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.07429) |
| 2024-05 | Iterative experience refinement of software- developing agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.04219) |
| 2024-04 | An artificial neuron for enhanced problem solving in large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2404.14222) |
| 2024-03 | Online adaptation of language models with a memory of amortized contexts | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.04317) |
| 2024-02 | Camelot: Towards large language models with training-free consolidated associative memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.13449) |
| 2023-08 | Retroformer: Retrospective large language agents with policy gradient optimization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.02151) |
| 2023-08 | ExpeL: LLM agents are experiential learners | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.10144) |
| 2023-06 | Synapse: Trajectory-as-exemplar prompting with memory for computer control | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2306.07863) |
| 2023-03 | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.11366) |
| 2020-09 | Meta-learning with sparse experience replay for lifelong language learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2009.04891) |

#### Long-horizon Agentic Task

| Date | Title | Paper |
|:------:|:------|:------:|
| 2025-10 | WebDART: Dynamic Decomposition and Re-planning for Complex Web Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.06587) |
| 2025-10 | CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.05520) |
| 2025-10 | Scaling LLM Multi-turn RL with End-to-end Summarization-based Context Management | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.06727) |
| 2025-09 | Efficient On-Device Agents via Adaptive Context Management | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=TPXVdBjrvU) |
| 2025-09 | WebWeaver: Structuring Web-Scale Evidence with Dynamic Outlines for Open-Ended Deep Research | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.13312) |
| 2025-09 | Prompt reinforcing for long-term planning of large language models | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=Xt6K4cw36l) |
| 2025-09 | Don’t Lose the Thread: Empowering Long-Horizon LLM Agents with Cognitive Resource Self-Allocation | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=NBGlItueYE) |
| 2025-09 | CEA: Context Engineering Agent for Enhanced Reliability and Sustainability in Deep Research Systems | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=6QUNblHtto) |
| 2025-09 | The Pensieve Paradigm: Stateful Language Models with Learned Memory Management | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=GymjF88oGQ) |
| 2025-09 | MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=XY8AaxDSLb) |
| 2025-09 | MemSearcher: Training LLMs to Reason, Search and Manage Memory via End-to-End Reinforcement Learning | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=EWIAx3NgvA) |
| 2025-09 | MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=k5nIOvYGCL) |
| 2025-09 | Compressed Step Information Memory for End-to-End Agent Foundation Models | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=vUG2hpVJWR) |
| 2025-09 | MemGen: Weaving Generative Latent Memory for Self-Evolving Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=vI56m4Iu4e) |
| 2025-09 | Intrinsic Memory Agents: Heterogeneous Multi-Agent LLM Systems through Structured Contextual Memory | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=UbSUxAK3BI) |
| 2025-09 | Learning on the Job: An Experience-Driven Self-Evolving Agent for Long-Horizon Tasks | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=ZzH6xDdpTP) |
| 2025-09 | Unifying Dynamic Tool Creation and Cross-Task Experience Sharing through Cognitive Memory Architecture | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=JnwClln80Q) |
| 2025-09 | From Experience to Strategy: Empowering LLM Agents with Trainable Graph Memory | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=bvaaydGKYp) |
| 2025-09 | MLE-RL: Reinforcement Learning for Self-Improvement in Machine Learning Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=nElqyHPHAz) |
| 2025-09 | ACON: Optimizing Context Compression for Long-horizon LLM Agents | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=7JbSwX6bNL) |
| 2025-09 | IterResearch: Rethinking Long-Horizon Agents via Markovian State Reconstruction | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=qQ5MZ5Mx7p) |
| 2025-09 | BrowserAgent: Building Web Agents with Human-Inspired Web Browsing Actions | [![Paper](https://img.shields.io/badge/Paper-6772E5?style=for-the-badge)](https://openreview.net/forum?id=dtExkh4l4z) |
| 2025-09 | PARL-MT: Learning to Call Functions in Multi-Turn Conversation with Progress Awareness | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23206) |
| 2025-08 | Sculptor: Empowering LLMs with Cognitive Agency via Active Context Management | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.04664) |
| 2025-08 | Cognitive Workspace: Active Memory Management for LLMs - An Empirical Study of Functional Infinite Context | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.13171) |
| 2025-08 | Chain-of-agents: End-to-end agent foundation models via multi-agent distillation and agentic rl | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.13167) |
| 2025-07 | MemTool: Optimizing Short-Term Memory Management for Dynamic Tool Calling in LLM Agent Multi-Turn Conversations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.21428) |
| 2025-06 | Code researcher: Deep research agent for large systems code and commit history | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.11060) |
| 2025-06 | Taskcraft: Automated generation of agentic tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.10055) |
| 2025-04 | Mem0: Building production-ready ai agents with scalable long-term memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.19413) |
| 2025-03 | Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.09572) |
| 2025-03 | Meminsight: Autonomous memory augmentation for llm agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.21760) |
| 2024-10 | From isolated conversations to hierarchical schemas: Dynamic tree memory representation for LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.14052) |
| 2024-10 | Web Agents with World Models: Learning and Leveraging Environment Dynamics in Web Navigation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.13232) |
| 2024-07 | Tree Search for Language Model Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.01476) |
| 2024-07 | Human-like episodic memory for infinite context llms | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.09450) |
| 2024-07 | AriGraph: Learning knowledge graph world models with episodic memory for LLM agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.04363) |
| 2023-10 | MemGPT: Towards LLMs as operating systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) |

### Survey

| Date | Title | Paper | GitHub |
| :------: | :------ | :------: | :------: |
| 2025-09 | The Landscape of Agentic Reinforcement Learning for LLMs: A Survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.02547) | [![GitHub Stars](https://img.shields.io/github/stars/xhyumiracle/Awesome-AgenticLLM-RL-Papers?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/xhyumiracle/Awesome-AgenticLLM-RL-Papers) |
| 2025-08 | OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.04482) | [![GitHub Stars](https://img.shields.io/github/stars/OS-Agent-Survey/OS-Agent-Survey?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/OS-Agent-Survey/OS-Agent-Survey) |
| 2025-08 | A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.07407) | [![GitHub Stars](https://img.shields.io/github/stars/EvoAgentX/Awesome-Self-Evolving-Agents?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents) |
| 2025-07 | A Survey of Context Engineering for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.13334) | [![GitHub Stars](https://img.shields.io/github/stars/Meirtz/Awesome-Context-Engineering?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/Meirtz/Awesome-Context-Engineering) |
| 2025-07 | A Survey of Self-Evolving Agents: On Path to Artificial Super Intelligence | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.21046) | [![GitHub Stars](https://img.shields.io/github/stars/CharlesQ9/Self-Evolving-Agents?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/CharlesQ9/Self-Evolving-Agents) |
| 2025-05 | Rethinking Memory in AI: Taxonomy, Operations, Topics, and Future Directions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.00675) | [![GitHub Stars](https://img.shields.io/github/stars/Elvin-Yiming-Du/Survey_Memory_in_AI?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/Elvin-Yiming-Du/Survey_Memory_in_AI) |
| 2025-04 | From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.15965) |  |
| 2025-04 | Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.01990) | [![GitHub Stars](https://img.shields.io/github/stars/FoundationAgents/awesome-foundation-agents?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/FoundationAgents/awesome-foundation-agents) |
| 2025-03 | Agentic Large Language Models, a survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.23037) |  |
| 2024-04 | A Survey on the Memory Mechanism of Large Language Model-based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2404.13501) | [![GitHub Stars](https://img.shields.io/github/stars/nuster1128/LLM_Agent_Memory_Survey?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/nuster1128/LLM_Agent_Memory_Survey) |

### Benchmark

| Date | Name | Title | Paper | GitHub |
| :------: | :------ | :------ | :------: | :------: |
| 2025-08 | StuLife | Building Self-Evolving Agents via Experience-Driven Lifelong Learning: A Framework and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.19005) | [![GitHub Stars](https://img.shields.io/github/stars/ECNU-ICALK/ELL-StuLife?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/ECNU-ICALK/ELL-StuLife) |
| 2025-07 | MemoryAgentBench | Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2507.05257) | [![GitHub Stars](https://img.shields.io/github/stars/HUST-AI-HYZ/MemoryAgentBench?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/HUST-AI-HYZ/MemoryAgentBench) |
| 2025-06 | StoryBench | StoryBench: A Dynamic Benchmark for Evaluating Long-Term Memory with Multi Turns | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.13356) |  |
| 2025-05 | LifelongAgentBench | LifelongAgentBench: Evaluating LLM Agents as Lifelong Learners | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.11942) | [![GitHub Stars](https://img.shields.io/github/stars/caixd-220529/LifelongAgentBench?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/caixd-220529/LifelongAgentBench) |
| 2025-02 | RealTalk | REALTALK: A 21-Day Real-World Dataset for Long-Term Conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.13270) | [![GitHub Stars](https://img.shields.io/github/stars/danny911kr/REALTALK?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/danny911kr/REALTALK) |
| 2024-10 | LongMemEval | LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2410.10813) | [![GitHub Stars](https://img.shields.io/github/stars/xiaowu0162/LongMemEval?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/xiaowu0162/LongMemEval) |
| 2024-02 | LoCoMo | Evaluating Very Long-Term Conversational Memory of LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.17753) | [![GitHub Stars](https://img.shields.io/github/stars/snap-research/locomo?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/snap-research/locomo) |

### Product & Project

| Date | Name | Title | Paper | Website | GitHub |
| :------: | :------ | :------ | :------: | :------: | :------: |
| 2025-05 | Cognee | Optimizing the Interface Between Knowledge Graphs and LLMs for Complex Reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.24478) | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://www.cognee.ai/) | [![GitHub Stars](https://img.shields.io/github/stars/topoteretes/cognee?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/topoteretes/cognee) |
| 2025-04 | Mem0 | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.19413) | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://mem0.ai/) | [![GitHub Stars](https://img.shields.io/github/stars/mem0ai/mem0?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/mem0ai/mem0) |
| 2023-10 | Letta | MemGPT: Towards LLMs as Operating Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://www.letta.com/) | [![GitHub Stars](https://img.shields.io/github/stars/letta-ai/letta?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/letta-ai/letta) |
|  | LangChain |  |  | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://www.langchain.com/) | [![GitHub Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/langchain-ai/langchain) |
|  | ReMe |  |  | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://modelscope.github.io/ReMe/) | [![GitHub Stars](https://img.shields.io/github/stars/modelscope/ReMe?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/modelscope/ReMe) |
|  | Memary |  |  | [![Website](https://img.shields.io/badge/website-1F4E79?style=for-the-badge)](https://kingjulio8238.github.io/memarydocs/) | [![GitHub Stars](https://img.shields.io/github/stars/kingjulio8238/Memary?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/kingjulio8238/Memary) |
