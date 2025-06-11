---
title: "Python Code Generator - Large language Models" 
date: 2021-04-06
tags: ["GPT2","pytorch","transformers","Mistral","Qwen2.5", "gemma3", "continual pretraining", "finetuning"]
author: ["Hilda Schreiber-Ziegler", "Moritz-Maria von Igelfeld"]
description: "This paper describes the inner hedgehog, a psychological condition widespread in academia. Published in the Journal of Socio-Experimental Psychology, 2021." 
summary: "Using several case studies, this paper describes the inner hedgehog, a psychological condition widespread in academic occupations. The condition has lasting consequences and no known cure." 
cover:
    image: "paper3.png"
    alt: "Vizualisation of python code gen"
    relative: true
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Journal of Socio-Experimental Psychology"

---

---

##### Download

+ [Paper](report.pdf)
+ [Raw data](https://github.com/pmichaillat/michez-rule)

---

##### Abstract

This project focuses on enhancing programmer productivity through Python code generation using
lightweight Large Language Models (LLMs). The primary objective is to develop compact LLMs capable
of running locally on personal hardware, thereby addressing privacy concerns associated with cloud-based
solutions. Two approaches were explored: (1) building models from scratch via pretraining and subsequent fine-tuning, and (2) fine-tuning existing pre-trained models. A range of architectures, including
GPT-2, Gemma 3, LLaMA 3.2, and Qwen 2.5 series, were evaluated for their effectiveness in code generation tasks. Experimental results indicate that the LLaMA 3.2 3B model consistently outperformed other
candidates. This work demonstrates the viability of small, local LLMs as practical coding assistants,
paving the way for privacy-preserving AI tools in software development.

---

##### Citation

Sashank T, Jagath K, and Junaid Ahmad. 2025. "Python Code Generation using LLM"

```BibTeX
@article{SZI21,
author = {Hilda Schreiber-Ziegler and Moritz-Maria von Igelfeld},
year = {2021},
title ={Your Inner Hedgehog},
journal = {Journal of Socio-Experimental Psychology},
volume = {131},
number = {2},
pages = {1299--1302}}
```

---

##### Related material

+ [Nontechnical summary](https://www.alexandermccallsmith.com/book/your-inner-hedgehog)
