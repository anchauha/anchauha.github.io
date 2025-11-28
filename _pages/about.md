---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there! I am currently an AI Researcher at [School of Education](https://education.indianapolis.iu.edu/index.html) department of [Indiana University Indianapolis](https://indianapolis.iu.edu). I work with [Dr. Jeremy Price](https://education.indianapolis.iu.edu/faculty-research/faculty-directory/price-jeremy.html) on LLM based methods that turn community generated data into structured knowledge graphs for analysis and retrieval.

I received my Master's in Applied Data Science from [Indiana University Indianapolis](https://indianapolis.iu.edu), where I was advised by [Dr. Sunandan Chakraborty](https://luddy.indianapolis.iu.edu/contact/directory/sunandan-chakraborty.html). My research specifically focused on cultural alignment in large language models, drawing on NLP and human-centered AI in education. The research was funded by [NSF grant](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2334631)

Research
======
My near term research interests focus on visual perception for decision making and planning in embodied AI agents, with an emphasis on socially aware Human Robot Interaction (HRI). 

<p align="center">
  <a href="https://github.com/anchauha">GitHub</a> &nbsp;/&nbsp;
  <a href="https://www.linkedin.com/in/chauhan-aankit/">LinkedIn</a>
</p>

Education
======
- M.S. in Applied Data Science, Indiana University Indianapolis, 2025
- B.Sc. in Information Technology, Univesity of Mumbai, 2023

Other Works
======

### Benchmarking LLMs for Pairwise Causal Discovery in Biomedical and Multi-Domain Contexts
> 2025  
- Managed the experimental code for evaluation for pairwise causal discovery (PCD), benchmarking 13 open-source LLMs on 12 diverse datasets using various prompting styles (few-shot, COT, FICL, ReAct, etc) and advanced span-scoring (Hungarian matching, SentenceLM similarity).
- Benchmarked detection and extraction capabilities of LLMs with DeepSeek-R1-Distill-Llama-70B attaining top causal detection accuracy (49.57%) and Qwen2.5-Coder-32B-Instruct led causal-pair extraction (47.12%).
- Ensured robust evaluation (8 expert annotators, inter annotator k = 0.758) and released a reproducible benchmark contributing to a publication on LLM's causal reasoning capabilities.

### Cultural Eval: Quantifying Cultural Bias in LLMs - Independent Study
> 2024  
- Developed a quantitative framework to benchmark cultural bias in LLMs by applying PCA to extract 5 latent cultural dimensions from 97,000 records across 96 variables of [WVS Dataset](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp)
- Compared responses from Llama-2 13B, Gemma 3 12B, and Phi 4 across 5 extracted latent cultural dimensions using Tucker's Congruence Coefficient and Cohen's d, revealing consistent underestimation of Religious-Traditional values for non-Western demographic profiles (Cohen's d: -0.89 to -1.17) [Visualization](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/regional_bias_heatmap_all_models.png)
- Created Western Bias Index and Overall Cultural Bias Index metrics, finding Llama-2 demonstrated the strongest [Western bias (WBI = 1.34)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/western_bias_index.png) and Phi 4 the highest overall [cultural bias (OCBI = 0.78)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/overall_cultural_bias_index.png).

### Mod-Guide: An LLM-based Content Moderation Feedback System
> 2024  
- Prototyped a multimodal NLP workflow processing 200 community collected text, image and audio documents of hate speech against minority voices in Bangladesh. Augmented the data with custom chain-of-thought reasoning, grounded in external knowledge sources, to generate [contextual metadata](https://github.com/anchauha/BanglaRAG/blob/main/data/Structured_RAG.pdf)
- The final model's performance was evaluated on a 50 example held out set where our GPT-4 + RAG system achieved an F1 score of 87% at detecting culturally nuanced hate speech compared to an F1 score of 64% from the zero-shot GPT-4 baseline.

Profile
=====
- [LinkedIn](https://www.linkedin.com/in/chauhan-aankit/)

Contact
=====
- [Gmail](mailto:ankichau.1718@gmail.com)
