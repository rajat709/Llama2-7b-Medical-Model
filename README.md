---
title: Llama 2 7b Med Model
emoji: ⚕️
colorFrom: purple
colorTo: indigo
sdk: gradio
sdk_version: 3.48.0
app_file: app.py
pinned: false
---

App URL: https://rjvishwa-rajat-llama-2-7b-med-model.hf.space/

Model: https://huggingface.co/rjvishwa/Llama-2-7b-Med-Model/tree/main

### Dataset Overview

| Name                 |  Source                                                                 |  n       |  n included in training |
|----------------------|-------------------------------------------------------------------------|----------|-------------------------|
| Medical Flashcards   |  [medalpaca/medical_meadow_medical_flashcards](https://huggingface.co/datasets/medalpaca/medical_meadow_medical_flashcards)  |  33955  |  33955                 |
| Wikidoc              |  [medalpaca/medical_meadow_wikidoc](https://huggingface.co/datasets/medalpaca/medical_meadow_wikidoc)    |  67704  |  10000                 |
| Wikidoc Patient Information | [medalpaca/medical_meadow_wikidoc_patient_information](https://huggingface.co/datasets/medalpaca/medical_meadow_wikidoc_patient_information)    |  5942 |  5942 |
| Stackexchange academia |  [medalpaca/medical_meadow_stack_exchange](https://huggingface.co/medalpaca/datasets/medalpaca/medical_meadow_stackexchange)    |  40865  |  40865                 |
| Stackexchange biology |  [medalpaca/medical_meadow_stack_exchange](https://huggingface.co/medalpaca/datasets/medalpaca/medical_meadow_stackexchange)    |  27887  |  27887                 |
| Stackexchange fitness |  [medalpaca/medical_meadow_stack_exchange](https://huggingface.co/medalpaca/datasets/medalpaca/medical_meadow_stackexchange)    |  9833  | 9833                 |
| Stackexchange health |  [medalpaca/medical_meadow_stack_exchange](https://huggingface.co/medalpaca/datasets/medalpaca/medical_meadow_stackexchange)    |  7721  |  7721                 |
| Stackexchange bioinformatics |  [medalpaca/medical_meadow_stack_exchange](https://huggingface.co/datasets/medalpaca/medical_meadow_stackexchange)    |  5407  |  5407                |
| USMLE Self Assessment Step 1 |  [medalpaca/medical_meadow_usmle_self](https://huggingface.co/datasets/medalpaca/medical_meadow_usmle_self_assessment)    |  119  |  92 (test only)              |
| USMLE Self Assessment Step 2 |  [medalpaca/medical_meadow_usmle_self](https://huggingface.co/datasets/medalpaca/medical_meadow_usmle_self_assessment)    |  120  |  110  (test only)              |
| USMLE Self Assessment Step 3 |  [medalpaca/medical_meadow_usmle_self](https://huggingface.co/datasets/medalpaca/medical_meadow_usmle_self_assessment)    |  135  |  122  (test only)             |
| MEDIQA               | [original](https://osf.io/fyg46/?view_only=), [preprocessed](https://huggingface.co/datasets/medalpaca/medical_meadow_mediqa) |  2208    |  2208 |
| CORD-19              | [original](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge ), [preprocessed](https://huggingface.co/datasets/medalpaca/medical_meadow_cord19) |  1056660    |  50000 |
| MMMLU               | [original](https://github.com/hendrycks/test), [preprocessed](https://huggingface.co/datasets/medalpaca/medical_meadow_mmmlu) |  3787    |  3787 |
| Pubmed Health Advice | [original](https://aclanthology.org/D19-1473/), [preprocessed](vhuggingface.co/datasets/medalpaca/health_advice) |  10178    |  10178 |
| Pubmed Causal               | [original](https://aclanthology.org/2020.coling-main.427/    ), [preprocessed](https://huggingface.co/datasets/medalpaca/medical_meadow_pubmed_causal) |  2446    |  2446 |
| ChatDoctor               | [original](https://github.com/Kent0n-Li/ChatDoctor  ) |  215000    |  10000 |
| OpenAssistant | [original](https://huggingface.co/OpenAssistant) |  9209   | 9209     |

The Llama Med Model represents an advanced suite of large language models meticulously fine-tuned for the specific purpose of medical question-answering and dialogue applications. Our primary goal is to provide a comprehensive selection of open-source language models, thereby facilitating the streamlined development of medical chatbot solutions.

The Meta Llama2 model, boasting an impressive 7 billion parameters, has been fine-tuned on a meticulously curated medical dataset. This training process was conducted on a robust infrastructure comprising two GPU nodes, each equipped with 15 GB of VRAM. Remarkably, this intricate training endeavor was successfully completed in a mere 8 hours.
