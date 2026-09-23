<div align="center">

# Reema Sarkar

**applied ML · LLM reliability · distributed systems**

<!-- add your contact badges here, e.g.
<a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/email-f4a7b9?style=flat&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/YOUR_HANDLE"><img src="https://img.shields.io/badge/LinkedIn-a7c7e7?style=flat&logo=linkedin&logoColor=white" /></a>
-->

</div>

### about me

I like taking research papers and turning them into running, tested code, on both
the ML side and the systems side. On the ML side, most of what I build is about one
question: **can we trust what the model says?** That covers hallucination detection,
retrieval that checks itself, and evaluation harnesses that report the honest number.
On the systems side, I like building the plumbing underneath: replication, consistency,
failure handling, and learned components inside real databases.

### things i've built

| project | what it is | highlights |
|---|---|---|
| **[selfcheckgpt-hallucination-detection](https://github.com/reema-s1/selfcheckgpt-hallucination-detection)** | Reproduction of *SelfCheckGPT* (Manakul et al., 2023): zero-resource, black-box hallucination detection from sample consistency | matches the paper within **0.05 pts** on all reported metrics (238 passages, 1,908 sentences) · batched DeBERTa NLI scoring · resumable eval · 17 tests + CI |
| **[corrective-rag](https://github.com/reema-s1/corrective-rag)** | From-scratch *Corrective RAG* (Yan et al., 2024): an LLM judge grades each retrieved doc, then the pipeline keeps it, refines it, or falls back to web search | **85% vs 40%** correct-and-grounded over plain RAG · **95%** routing accuracy · cited answers · FastAPI service · JSONL run logs |
| **[steerdb-bao](https://github.com/reema-s1/steerdb-bao)** | *Bao*-style learned query optimizer: a PyTorch Tree-CNN over Postgres `EXPLAIN` plans picks a hint set for each query | uncertainty-aware (Thompson sampling) + confidence safety guard · cross-validated ablations · Dockerized |
| **[quorum](https://github.com/reema-s1/quorum)** | Distributed key-value store, grown from a single-node engine with a write-ahead log into a multi-node cluster over TCP | consistent hashing · N-way replication · tunable `ONE` / `QUORUM` / `ALL` consistency · heartbeat failure detection · hinted handoff · Merkle-tree anti-entropy |
| **[sentiment-finetune](https://github.com/reema-s1/sentiment-finetune)** | Fine-tuned DistilBERT vs a TF-IDF + logistic regression baseline | the baseline won on 2k examples, so I did error analysis and diagnosed the overfitting |

### what i care about

- **papers → code.** reading a paper, reproducing it, and checking my numbers against theirs
- **grounding & factual consistency.** hallucination detection, citation-checked RAG, LLM-as-judge evals
- **evaluation.** AUC-PR, correlation, calibrated uncertainty, baselines, and caveats stated upfront
- **distributed systems.** replication, quorum consistency, failure detection, and replica repair
- **production-shaped ML.** modular Python, tests that don't need model downloads, Docker, REST APIs

### stack

**ML / NLP**
<br/>
<img src="https://img.shields.io/badge/PyTorch-f4a7b9?style=flat&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-f4a7b9?style=flat&logo=huggingface&logoColor=white" />
<img src="https://img.shields.io/badge/Transformers-f4a7b9?style=flat" />
<img src="https://img.shields.io/badge/scikit--learn-f4a7b9?style=flat&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/LightGBM-f4a7b9?style=flat" />

**LLMs / Retrieval**
<br/>
<img src="https://img.shields.io/badge/RAG-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/FAISS-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/LLM--as--judge-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/NLI-c3b1e1?style=flat" />
<img src="https://img.shields.io/badge/Anthropic%20%2F%20OpenAI%20APIs-c3b1e1?style=flat" />

**Distributed Systems**
<br/>
<img src="https://img.shields.io/badge/Consistent%20Hashing-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/Replication-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/Quorum%20Consistency-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/Merkle%20Trees-b5d8cc?style=flat" />
<img src="https://img.shields.io/badge/TCP%20Networking-b5d8cc?style=flat" />

**Backend / Infra**
<br/>
<img src="https://img.shields.io/badge/Python-a7c7e7?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-a7c7e7?style=flat&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-a7c7e7?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-a7c7e7?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/pytest-a7c7e7?style=flat&logo=pytest&logoColor=white" />
