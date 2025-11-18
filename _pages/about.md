---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am AI Engineer at Indiana University, Indianapolis who recently graduated from Indiana University, Indianapolis with a Master's in Applied Data Science. My research interests lie at the intersection of human-robot interaction, machine learning, and computer vision.

Education
======
- M.S. in Applied Data Science, Indiana University Indianapolis, 2025
- B.Sc. in Information Technology, Univesity of Mumbai, 2023

Work Experience
======

## AI Engineer - Indiana University Indianapolis
> Aug 2025 - Present

- Developed and containerized a [full stack knowledge graph app](https://github.com/CEnTRInnovations/CentrMap_v1) with 36 endpoint API (FastAPI), interactive graph visualizations (Cytoscape.js), and a responsive UI (React, TypeScript) to help the organization visualize complex community relationships.
- Designed a Neo4j graph database schema (10 node/11 relationship types) based on an Ecological Systems Model, writing advanced Cypher queries for managing complex linking between people, programs, and assets and orphan detection for data integrity.
- Engineered a weak supervision pipeline and fine-tuned a [BERT model](https://github.com/anchauha/asset-deficit-miner/blob/main/bert_finetuning/models/bert-v1/best_model/experiment_results.json) to classify asset-deficit language, expanding a 270 example seed set [IU Press Release](https://github.com/anchauha/asset-deficit-miner/blob/main/process_with_llm/data/output/results_gemini-2.5-Instruct_semantic_extraction_prompt3_d689d527.json) by 5x into a 1,350-example corpus.
- Deployed the fine-tuned BERT classifier (0.68 F1 score) as a containerized Flask app, optimizing the inference endpoint to a p95 latency of 3.4s under load.

## Research Assistant (AI) - Indiana University Indianapolis
> Aug 2023 - May 2025
- Led research and development of [CATpc: Critical Activity Teacher Planning Companion (First Prototype)](https://github.com/anchauha/CATpc) for an [NSF funded research grant](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2334631) under the esteemed guidance of [Prof. Sunandan Chakraborty](https://luddy.indianapolis.iu.edu/contact/directory/sunandan-chakraborty.html) & [Dr. Jeremy Price](https://education.indianapolis.iu.edu/faculty-research/faculty-directory/price-jeremy.html). The final system demonstrated 14% higher pedagogical alignment scores, 8% reduced hallucinations, and 27% increased teacher satisfaction compared to GPT-3.5 baseline.
- Built CoDe-KG, a knowledge graph extraction pipeline, by producing a sentence complexity dataset from 7,500 PubMed lung cancer abstracts, fine-tuning BERT variants on the dataset. Generated a labeled corpus by classifying on coreference resolved abstracts. Processed corpus with various prompting strategies (GIP, CoT, FICL, Hybrid) to perform sentence simplification and extract relationships (knowledge triples).
- Benchmarked the triple extraction pipeline on standard relation extraction tasks, achieving 92.4% F1 on 398 gold standard triples. Outperformed prior methods with an +8% macro-F1 improvement on the ReBEL benchmark (65.78% vs previous ~57%).
- Supported over 30 students as a TA  in the Fall 2024 H518 Deep Learning course through tutorials, labs, office hours, and lesson planning on topics like AlexNet, LSTM, Transformers, word2vec, BERT, GAN, and Reinforcement Learning.

## Cloud Consultant (Data & Machine Learning Platforms) - Capgemini
> Apr 2020 - Sep 2022

- Engineered a data ingestion pipeline using PySpark to load data into 100+ Hive tables, reducing data processing time by 40%.
- Built an XGBoost based predictive forecasting model that optimizes SKU selection for enterprise licensing needs. This benefited in 18% annual cost savings on underutilized license spend for 43,000+ users.
- Developed Cloud Functions to process and load over 10 GB of daily raw JSON data from GCS bucket into BigQuery and Cloud SQL.
- Led migration for legacy applications to Azure cloud environment during an enterprise split ensuring service continuity for over 23,000 users.

#### Cloud Consultant (Cloud Infrastructure & DevOps) - Wipro
> Jul 2018 - Mar 2020
- Developed federated workflows for Azure infrastructure provisioning, managing 250+ virtual machines with 99.9% uptime.
- Designed and maintained Azure DevOps pipelines for deployments to Azure App Services for 20+ business and operations applications, cutting deployment time by ~30%.
- Authored 20 knowledge base documents on routine administration tasks and contributed to regular knowledge sharing sessions on topics such as storage lifecycle, retention, and Azure CLI across EMEA, APAC, and NA teams.

Other Works
======

## Benchmarking LLMs for Pairwise Causal Discovery in Biomedical and Multi-Domain Contexts
> 2025
- Managed the experimental code for evaluation for pairwise causal discovery (PCD), benchmarking 13 open-source LLMs on 12 diverse datasets using various prompting styles (few-shot, COT, FICL, ReAct, etc) and advanced span-scoring (Hungarian matching, SentenceLM similarity).
- Benchmarked detection and extraction capabilities of LLMs with DeepSeek-R1-Distill-Llama-70B attaining top causal detection accuracy (49.57%) and Qwen2.5-Coder-32B-Instruct led causal-pair extraction (47.12%).
- Ensured robust evaluation (8 expert annotators, inter annotator k = 0.758) and released a reproducible benchmark contributing to a publication on LLM's causal reasoning capabilities.

## Cultural Eval: Quantifying Cultural Bias in LLMs - Independent Study
> 2024
- Developed a quantitative framework to benchmark cultural bias in LLMs by applying PCA to extract 5 latent cultural dimensions from 97,000 records across 96 variables of [WVS Dataset](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp)
- Compared responses from Llama-2 13B, Gemma 3 12B, and Phi 4 across 5 extracted latent cultural dimensions using Tucker's Congruence Coefficient and Cohen's d, revealing consistent underestimation of Religious-Traditional values for non-Western demographic profiles (Cohen's d: -0.89 to -1.17) [Visualization](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/regional_bias_heatmap_all_models.png)
- Created Western Bias Index and Overall Cultural Bias Index metrics, finding Llama-2 demonstrated the strongest [Western bias (WBI = 1.34)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/western_bias_index.png) and Phi 4 the highest overall [cultural bias (OCBI = 0.78)](https://github.com/anchauha/CultureEval/blob/main/output/efa_comparison_all_models/visualizations/overall_cultural_bias_index.png).

## Mod-Guide: An LLM-based Content Moderation Feedback System
> 2024
- Prototyped a multimodal NLP workflow processing 200 community collected text, image and audio documents of hate speech against minority voices in Bangladesh. Augmented the data with custom chain-of-thought reasoning, grounded in external knowledge sources, to generate [contextual metadata](https://github.com/anchauha/BanglaRAG/blob/main/data/Structured_RAG.pdf)
- The final model's performance was evaluated on a 50 example held out set where our GPT-4 + RAG system achieved an F1 score of 87% at detecting culturally nuanced hate speech compared to an F1 score of 64% from the zero-shot GPT-4 baseline.

Profile
=====
* [LinkedIn](https://www.linkedin.com/in/chauhan-aankit/)

Contact
=====
* [Gmail](mailto:ankichau.1718@gmail.com)
