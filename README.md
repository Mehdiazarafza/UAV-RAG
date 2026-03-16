##  RAG-UAV

A repository for evaluating Large Language Models (LLMs) in Unmanned Aerial Vehicle (UAV) applications using Retrieval-Augmented Generation (RAG).
This work was accepted at ICLR 2026 Workshop on Logical Reasoning of Large Language Models.

---
##  Contents

This repository is organized into the following folders:

- **`Answers/`** — Contains the answers from the expert for UAV-application.
- **`Models/`** — Includes the LLMs generated answers for the questions.
- **`Questions/`** — Stores domain-specific questions related to UAV operations.
- **`Paper/`** — Holds research papers used for building the RAG knowledge base.

---

## Models

Section for LLM output:

*  **LLama 3.2:**  [ LLama 3.2 3B](Models/Llama3.2/Answer)
*  **Mistral:**  [Mistral 7B](Models/Mistral/Answer)
*  **GPT o1-preview:**  [ o1-preview](Models/o1-preview/Answer)
*  **GPT-4 Turbo:**  [ GPT-4 Turbo](Models/Turbo/Answer)
*  **Deep Seek:**  [ Deep Seek](Models/DeepSeek/DeepSeek70b/Answer)
*  **LLama 3.3:**  [ Llama 3.3 70B ](Models/Llama3.3/Answer)
*  **Open AI o1:**  [ o1 ](Models/o1/Answer)
*  **ChatGPT website:**  [ ChatGPT ](Models/ChatGPT/Answer)




##  BibTeX

If you find **RAG-UAV** useful for your research or applications, please cite it using the following BibTeX:


```bibtex
@misc{uav-rag-Azarafza,
  title     = {Mathematical Reasoning for Unmanned Aerial Vehicles: A RAG-Based Approach for Complex Arithmetic Reasoning},
  author    = {Mehdi Azarafza and Mojtaba Nayyeri and Faeze Pasandideh and Steffen Staab and Achim Rettberg},
  year      = {2025},
  eprint    = {2506.04998},
  archivePrefix = {arXiv},
  primaryClass = {cs.AI},
  url       = {https://arxiv.org/pdf/2506.04998}
}
@inproceedings{
azarafza2026mathematical,
title={{MATHEMATICAL} {REASONING} {FOR} {UNMANNED} {AERIAL} {VEHICLES}: A {RAG}-{BASED} {APPROACH} {FOR} {COMPLEX} {ARITHMETIC} {REASONING}},
author={Mehdi Azarafza and Mojtaba Nayyeri and Faezeh Pasandideh and Steffen Staab and Achim Rettberg},
booktitle={ICLR 2026 Workshop on Logical Reasoning of Large Language Models},
year={2026},
url={https://openreview.net/forum?id=NYYG1RlCLM}
}
