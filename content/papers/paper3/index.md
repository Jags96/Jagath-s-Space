---
title: "Python Code Generator - Large language Models" 
date: 2025-03-26
tags: ["GPT2","pytorch","transformers","Mistral","Qwen2.5", "LLaMa","gemma3", "continual pretraining", "finetuning"]
author: ["Jagath Kumar Reddy K"]
description: "This paper describes the experimental setup, observation and analysis of Continual pretraining of GPT2 , finetuning of Gemma3 LLaMa 3.2 and Qwen 2.5 to produce a Python Code Generator" 
summary: "" 
cover:
    image: "paper3.png"
    alt: "Vizualisation of python code gen"
    relative: true
---

---

##### Download

+ [Paper](report.pdf)
+ [Pretraining dataset](https://huggingface.co/datasets/codeparrot/codeparrot-clean)
+ [Finetuning dataset](https://huggingface.co/datasets/iamtarun/python_code_instructions_18k_alpaca)
+ [Code](https://github.com/Jags96/PythonCodeGen-Repo)

---

##### Abstract

This project focuses on enhancing programmer productivity through Python code generation using
lightweight Large Language Models (LLMs). The primary objective is to develop compact LLMs capable
of running locally on personal hardware, thereby addressing privacy concerns associated with cloud-based
solutions. Two approaches were explored: (1) building models from scratch via pretraining and subsequent fine-tuning, and (2) fine-tuning existing pre-trained models. A range of architectures, including GPT-2, Gemma 3, LLaMA 3.2, and Qwen 2.5 series, were evaluated for their effectiveness in code generation tasks. Experimental results indicate that the LLaMA 3.2 3B model consistently outperformed other
candidates. This work demonstrates the viability of small, local LLMs as practical coding assistants,
paving the way for privacy-preserving AI tools in software development.

---

##### Citation

Sashank T, Jagath K, and Junaid Ahmad. 2025. "Python Code Generation using LLM"

```BibTeX
@techreport{TalakolaKatama2025nlp,
  author      = {Sashank Reddy Talakola and Jagath Kumar Reddy Katama Reddy},
  title       = {Python Code Generation using Large Language Models},
  institution = {Indiana University},
  year        = {2025},
  type        = {Final Project Report},
  note        = {Submitted for NLP course at Indiana University}
}
```

---

##### Related material

+ [Nontechnical summary blog]()
