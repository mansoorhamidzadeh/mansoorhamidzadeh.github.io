---
title: About
layout: default
nav_order: 2
---

# About

Generative AI engineer with 2+ years of hands-on experience designing and shipping
production LLM systems — multi-agent pipelines, Graph RAG on Neo4j, and high-throughput
inference on vLLM/SGLang. I am happiest working on open problems where the architecture
does not exist yet, rather than implementing established patterns. I am a co-author of
the HAFEZ Persian language model paper, and my current R&D interests are multi-agent
reasoning, AI safety, and AI for medicine.

## Experience

### Generative AI Engineer — Rokam Co.
Tehran, Iran · February 2025 – Present

- Design and build multi-agent systems for complex reasoning and research tasks, using
  LangGraph, locally served LLMs via MCP, and a Neo4j knowledge layer, with pipelines
  instrumented in Langfuse for tracing and evaluation.
- Built knowledge-graph systems on Neo4j with LLM-driven schema inference over
  semi-structured data, including entity resolution and conflict alignment, with no
  predefined schemas. Took the system from concept to a working MVP in about 3–4 months;
  it has processed 3,000+ entities end-to-end.
- Designed adaptive multi-path agent routing that picks a strategy based on query
  complexity — from lightweight retrieval to multi-agent orchestration and multi-agent
  debate for high-stakes reasoning.
- Own the production LLM inference layer: vLLM and SGLang serving LLMs, VLMs, and
  multimodal models, plus a custom provider for structured NER via constrained decoding.

### AI Engineer (Freelance / Contract) — Viravirast
Tehran, Iran (Remote) · March 2024 – Present

- Built an agentic LLM workflow with LangGraph for a Persian-language conversational
  use case.
- Continued collaboration with the HAFEZ co-author on Persian NLP research and dataset
  work, contributing to evaluation pipelines and NER tooling for Persian literary
  contexts.

### NLP Engineer (promoted from AI R&D Intern) — Sepehr Mahan Tech
Tehran, Iran · December 2023 – January 2025

- Sole AI engineer on staff; owned the full AI roadmap from research and prototyping to
  production deployment across NLP, retrieval, and conversational systems.
- Fine-tuned Persian BERT and BERTopic models for classification and topic modeling on
  Persian enterprise data, and trained a custom Persian NER model.
- Co-authored the HAFEZ paper as second author, leading dataset curation and benchmark
  preparation for evaluating Persian language models in the humanities domain.

### Mandatory Military Service
2021 – 2023

- Two years of compulsory military service, prior to transitioning into AI engineering.

## Publication

**HAFEZ: Advanced Persian Language Model for Analysis and Processing of Humanities
Texts** — Rahmani A., Hamidzadeh M., Iravani A.M., Ebrahimkhani O., Estakhri N.,
Sajjadi S.M., Moshiri A. 7th National Conference on Computational Linguistics, Iranian
Linguistics Association & Institute for Humanities and Cultural Studies, 2024.

Second author. Led dataset curation and benchmark preparation for evaluating Persian
language models on humanities and literary texts.

## Education

**Bachelor of Software Engineering**, Islamic Azad University, South Tehran Branch,
2016 – 2020. GPA 16.68 / 20 (≈ 3.34 / 4.00).

## Skills

**LLM engineering** — fine-tuning (LoRA / PEFT / SFT), RAG, Graph RAG, prompt
engineering, constrained decoding, structured output (Pydantic)

**Agents & orchestration** — LangGraph, LangChain, MCP (Model Context Protocol), A2A,
multi-agent debate, tool calling, agentic RAG

**Inference & serving** — vLLM, SGLang (PagedAttention, RadixAttention, continuous
batching), multimodal serving (LLM / VLM / OCR)

**Knowledge graphs & retrieval** — Neo4j, Cypher, LLM-driven schema inference, entity
resolution, Qdrant, ElasticSearch, Sentence-Transformers, hybrid retrieval

**Deep learning** — PyTorch, HuggingFace Transformers, TRL, BERT / BERTopic, custom
training loops

**Observability & evaluation** — Langfuse, DeepEval, RAGAS, TensorBoard, Label Studio

**Languages & infrastructure** — Python (FastAPI, Pydantic), SQL, PostgreSQL, Bash, Git,
Linux, Docker

## Research interests

Multi-agent systems and debate reasoning · graph-augmented LLMs and knowledge graph
construction · LLM fine-tuning and alignment (RLHF / DPO / Constitutional AI) · AI
safety and adversarial robustness · AI for medicine (drug discovery, brain–AI
integration)

## Languages

Persian (native) · Turkish (native — mother tongue) · English (professional working, B2)
