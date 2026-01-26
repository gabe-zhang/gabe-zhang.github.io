---
layout: page
title: Paper2Summary
description: Scientific paper summarization via LoRA fine-tuning
importance: 1
category: "LLM/NLP"
img: /assets/img/paper2summary-cover.jpg
---

### Quick Summary

- Developed a scientific paper summarization system by LoRA fine-tuning Llama-3.2-1B-Instruct on 20K arXiv papers, training only 0.07% of parameters (~850K) with 10K token context support (~28 hours on single RTX A6000)
- Achieved +51% ROUGE-2 and +37% ROUGE-3 improvement over base model on 6,440-sample test set

Tools: Python, PyTorch, PEFT, Hugging Face, Weights & Biases

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
