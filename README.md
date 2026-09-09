# Ahmad Zalmout

ML engineer in Bolzano, Italy. I build text classification, multilingual NLP,
and agentic systems that run in production, usually under real constraints:
limited hardware, messy institutional data, and three working languages.

**Available for contract and subcontract work.**

## What I do

**Text classification and document routing.** Fine-tuning open models on your
data, with a real evaluation section and a deployment path. Recently: a
multilingual classifier over 1,000+ job title categories across Italian,
German and English, taken from 54% to 82% accuracy and deployed to production
at a South Tyrolean public IT company.

**Agentic systems.** Multi-agent pipelines that do structured work end to end,
not chatbot demos. See `agentic-ml-pipeline-builder` below.

**Making models work under constraints.** CPU-only environments, on-prem
requirements, small labeled datasets, GPU memory limits. A chained Random
Forest pipeline imputing roughly one million missing occupation codes across a
5.5 million record contract database, reaching 75.76% accuracy on 700+ classes.
A domain-shift recovery from 0.50 to 0.77 accuracy using fewer than 140
labeled target-domain examples.

## Selected work

| Repository | What it shows |
|---|---|
| [agentic-ml-pipeline-builder](https://github.com/Ahmad-Zalmout/agentic-ml-pipeline-builder) | Seven-agent AutoGen system: task description and raw dataset in, deployable reviewed Python pipeline out |
| [multilingual-hierarchical-text-classification](https://github.com/Ahmad-Zalmout/multilingual-hierarchical-text-classification) | XLM-RoBERTa with a hierarchical classification head over multilingual occupation taxonomies |
| [cross-dataset-generalization](https://github.com/Ahmad-Zalmout/cross-dataset-generalization) | Diagnosing domain-shift collapse and recovering with linear probing on a tiny labeled set |

## Background

MSc Computing for Data Science, Free University of Bozen-Bolzano.
BSc Computer Science, Princess Sumaya University for Technology, Amman.
Previously IT audit at KPMG, which is why I can sit in a room with non-technical
stakeholders and a compliance officer and make sense to both.

Working languages: English, German (intermediate), Arabic (native),
Italian (basic).

## Stack

PyTorch, HuggingFace Transformers, AutoGen, scikit-learn, CUDA and mixed-precision
training, Databricks, Flask. Microsoft Certified: Azure AI Fundamentals.

## Contact

[LinkedIn](www.linkedin.com/in/ahmad-zalmout-a288b1224) · azalmout@gmail.com
