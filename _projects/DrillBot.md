---
layout: page
title: DrillBot
description: A multi-agent RAG system to answer drilling KPI queries
importance: 1
category: "LLM/RAG/AI"
img: /assets/img/DrillBot-cover.png
---

### Quick Summary

- Built a multi-agent RAG system to answer drilling KPI queries on time-series sensor data using LLMs and LangChain
- Compiled comprehensive drilling knowledge base with Nabors Industries, including 40+ terminology definitions, database schema metadata, and 50+ FAQ answers covering business contexts, Python, and SQL code for drilling KPIs
- Implemented Chain of Thought (CoT) prompting to enhance SQL code generation for the SQLCoder-7B-2 agent
- Improved semantic search and reranking using Sentence Transformers for initial retrieval and cross-encoder for reranking, achieving 0.95 cosine similarity for typical user queries

### Sample Architecture Diagram

{% include figure.liquid loading="eager" path="assets/img/DrillBot-architecture.png" title="example image" class="img-fluid rounded z-depth-1" %}
