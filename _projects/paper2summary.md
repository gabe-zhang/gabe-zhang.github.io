---
layout: page
title: paper2summary
description: A resource-efficient RAG engine for scientific paper question answering
importance: 1
category: "LLM/RAG/AI"
---

### Quick Summary

- Developed a RAG engine for scientific paper QA with accurate source citations
- Enhanced Llama-3.2-1B for paper summarization via LoRA fine-tuning (7% trainable parameters), achieving 51% higher ROUGE-2 and 13% ROUGE-L scores
- Deployed a hybrid text/vector retrieval system featuring LLM reranking and citation visualization on laptop hardware

Tools: PEFT, Transformers, Weights & Biases, Kotaemon, ChromaDB

### Video Demo

 <style>
    .video-container {
        position: relative;
        padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
        height: 0;
        overflow: hidden;
    }
    .video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: none;
    }
</style>
<div class="video-container">
<iframe 
    src="https://www.youtube.com/embed/NsxGwMrflAE" 
    title="YouTube video player" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>
</div>

For more detailed project information, please visit the GitHub repo: <https://github.com/gabe-zhang/paper2summary>
