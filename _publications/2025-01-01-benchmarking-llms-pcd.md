---
title: "Examining Pairwise Causal Discovery in open-source Large Language Models using Prompt Tuning"
collection: publications
permalink: /publication/2025-01-01-benchmarking-llms-pcd
header:
  teaser: "PCD_pipe.png"
# excerpt: 'We benchmark 13 open-source LLMs on pairwise causal discovery (PCD) across 12 datasets, evaluating both detection and span-level extraction with various prompting strategies.'
date: 2025-01-01
# venue: 'IEEE International Conference on Big Data (To appear)'
# paperurl: 'http://example.com/paper.pdf'  # Uncomment and update when available
# slidesurl: 'http://example.com/slides.pdf'  # Uncomment when available
citation: 'Sydney Anuyah, Sneha Shajee Mohan, Bofu Dong, <b>Ankit Singh Chauhan</b>, Sunandan Chakraborty. (2025). &quot;Examining Pairwise Causal Discovery in open-source Large Language Models using Prompt Tuning. &quot; <i>2025 IEEE International Conference on Big Data</i>.  (To appear)'
---

The safe deployment of large language models (LLMs) in high-stakes fields like biomedicine, requires them to be able to reason about cause and effect. We investigate this ability by testing 13 open-source LLMs on a fundamental task: pairwise causal discovery (PCD) from text. Our benchmark, using 12 diverse datasets, evaluates two core skills: 1) Causal Detection (identifying if a text contains a causal link) and 2) Causal Extraction (pulling out the exact cause and effect phrases). We tested various prompting methods, from simple instructions (zero-shot) to more complex strategies like Chain-of-Thought (CoT) and Few-shot In-Context Learning (FICL). The results show major deficiencies in current models. The best model for detection, DeepSeek-R1-Distill-Llama-70B, only achieved a mean score of 49.57% (Cdetect), while the best for extraction, Qwen2.5-Coder-32B-Instruct, reached just 47.12% (Cextract). Models performed best on simple, explicit, single sentence relations. However, performance plummeted for more difficult (and realistic) cases, such as implicit relationships, links spanning multiple sentences, and texts containing multiple causal pairs. We provide a unified evaluation framework, built on a dataset validated with high inter-annotator agreement (κ ≥ 0.758), and make all our data, code, and prompts publicly available to spur further research.

<!-- [Download paper here](http://example. com/paper.pdf) -->
<!-- [Download slides here](http://example.com/slides.pdf) -->
<!-- [Code repository](http://github.com/example/repo) -->
