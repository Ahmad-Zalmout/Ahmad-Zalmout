# Ahmad Zalmout

ML engineer in Bolzano, Italy. I build text classification, multilingual NLP,
and agentic systems that run in production, usually under real constraints:
limited hardware, messy institutional data, and three working languages.

**Available for contract and subcontract work.**

## What I do

**Classification of messy real-world records.** Imputing roughly 1.5 million
missing occupation codes across a 5.5 million record employment contract
database for a public labour market office, feeding official statistics:
75.88% accuracy across 700+ hierarchical classes, CPU-only. The first model
looked fine on accuracy but emitted 200+ codes that do not exist in the
national classification; redesigning it as a digit-by-digit chain cut that
to 45.

> "The results were useful for our work and showed clear potential for
> supporting data quality improvements and reducing manual coding effort."
>
> Walter Niedermair, Amt für Arbeitsmarktbeobachtung / Ufficio Osservazione
> mercato del lavoro, Bolzano

**Multilingual text classification.** Fine-tuning transformers with custom
hierarchical classification heads across Italian, German and English, taken
to production at a South Tyrolean public IT company.
<!-- When SIAG clears it: name SIAG, add "1,000+ categories, 54% to 82% accuracy" -->

**Agentic systems.** Multi-agent pipelines that do structured work end to end.
My current one takes a task description and a raw dataset and produces a
reviewed, deployable Python ML pipeline.

**Making models work with little data.** Recovering a video classifier from
chance level to 0.77 accuracy on a new domain using fewer than 140 labelled
examples.

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
