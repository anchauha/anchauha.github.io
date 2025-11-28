---
title: "Benchmarking LLMs for Pairwise Causal Discovery (PCD) in Biomedical and Multi-Domain Contexts"
collection: publications
category: manuscripts
permalink: /publication/2025-01-01-benchmarking-llms-pcd
excerpt: 'We benchmark 13 open-source LLMs on pairwise causal discovery (PCD) across 12 datasets, evaluating both detection and span-level extraction with various prompting strategies.'
date: 2025-01-01
venue: '2025 IEEE International Conference on Big Data'
# paperurl: 'http://example.com/paper.pdf'  # Uncomment and update when available
# slidesurl: 'http://example.com/slides.pdf'  # Uncomment when available
citation: 'Sydney Anuyah, Sneha Shajee Mohan, Bofu Dong, <b>Ankit Singh Chauhan</b>, Sunandan Chakraborty. (2025). &quot;Benchmarking LLMs for Pairwise Causal Discovery (PCD) in Biomedical and Multi-Domain Contexts. &quot; <i>2025 IEEE International Conference on Big Data</i>.  (To appear)'
---

We benchmark 13 open-source LLMs on pairwise causal discovery (PCD) across 12 datasets, evaluating both detection (1a–1d) and span-level extraction (2a–2h).  For detection, we compare instruction-only, few-shot in-context learning (FICL), chain-of-thought (CoT), and hybrid CoT+FICL; for extraction, we additionally test Least-to-Most and ReAct prompting. We score spans with Hungarian matching and a calibrated SentenceLM-based similarity scheme. Results show DeepSeek-R1-Distill-Llama-70B has the highest mean detection performance (Cdetect = 49.57%), while Qwen2.5-Coder-32B-Instruct leads mean extraction (Cextract = 47. 12%). Overall performance is strongest on explicit, intra-sentential relations, while implicit, inter-sentential, and multi-pair cases remain more challenging. Eight annotators achieved κ ≥ 0.758 before adjudication. 

<!-- [Download paper here](http://example. com/paper.pdf) -->
<!-- [Download slides here](http://example.com/slides.pdf) -->
<!-- [Code repository](http://github.com/example/repo) -->