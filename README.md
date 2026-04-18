# Retrieval-Augmented Generation (RAG) / Fine Tuning
Comparing RAG and Fine-tuning mechanisms on LLaMA 3.2-1B for Question Answering(on SciQ dataset)

This project presents a comparative study between Retrieval-Augmented Generation (RAG) and fine-tuning approaches using a domain-specific dataset. The goal is to evaluate how each method performs in terms of accuracy and effectiveness when applied to scientific question-answering tasks.

**Dataset**
We use the SciQ dataset, a scientific-domain dataset consisting of crowdsourced multiple-choice questions, supporting context passages
and answer annotations.

This dataset is particularly suitable for evaluating models in knowledge-intensive and context-aware tasks.

**Methodology**

1. Retrieval-Augmented Generation (RAG)
Combines retrieval mechanisms with generative models
Uses embedding models to fetch relevant context
Enhances response quality with external knowledge grounding
2. Fine-Tuning
Pretrained language models are fine-tuned directly on the SciQ dataset
Focuses on adapting model weights to the domain-specific distribution

**Model Selection**
All models used in this study—including language models and embedding models were selected after a comprehensive review of relevant research papers and empirical evaluation.

**Hyperparameter Tuning**
For fine-tuning, hyperparameters were carefully optimized. For example:

Learning rates tested:
3e-5
2e-5
1e-5
Selected learning rate: 2e-5
Chosen based on achieving the highest accuracy during experiments. This systematic approach was applied across all major configuration choices.

**Objective**
The primary objective is to:

1. Compare performance between RAG and fine-tuned models
2. Analyze trade-offs between retrieval-based and parametric knowledge
3. Identify the most effective approach for domain-specific QA tasks

If you're interested in the full research details, regarding model selection and experimental design please reach out: vargheseremy97@gmail.com
