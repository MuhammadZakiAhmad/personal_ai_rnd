# Personal AI Research & Development

**Muhammad Zaki Ahmad**

This repository documents my exploration of modern artificial intelligence through **first-principles implementations, architectural studies, and applied experiments**.

My primary interests include **foundation models, large language models, vision-language models, agentic AI, representation learning, and world models**. I use implementation as a way to develop a deeper understanding of the architectural, mathematical, and computational foundations underlying modern AI systems.

> **Scope:** This repository contains a combination of educational implementations, architectural reproductions, and applied projects. Implementations of existing architectures are intended for learning and experimentation and are not presented as original model contributions.

---

## Research Interests

**Foundation Models**
LLM architectures, Transformer architectures, efficient attention, positional representations

**LLM Reasoning**
Reasoning enhancement, representation learning, distillation, parameter-efficient adaptation

**Agentic AI**
Planning, tool use, memory, multi-step execution, multi-agent systems

**Multimodal Learning**
Vision-language models, multimodal representations, visual-textual learning

**World Models**
Predictive learning, temporal dynamics, environment modelling

**Computer Vision**
Object detection, tracking, pose estimation, 3D human reconstruction

---

# First-Principles Implementations

A central focus of this repository is implementing modern AI architectures and their underlying components rather than relying exclusively on high-level abstractions.

## Large Language Models

| Implementation                                           | Description                                                             |
| -------------------------------------------------------- | ----------------------------------------------------------------------- |
| [`LLM_GPT_2_from_scratch/`](./LLM_GPT_2_from_scratch/)   | GPT-2 implementation based on the decoder-only Transformer architecture |
| [`LLM_gemma_from_scratch/`](./LLM_gemma_from_scratch/)   | Gemma architecture implemented from its fundamental components          |
| [`LLM_qwen_3_from_scratch/`](./LLM_qwen_3_from_scratch/) | Qwen 3 architecture implemented in PyTorch                              |

## Transformer Internals

| Implementation                                                       | Description                                                                 |
| -------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [`SELF_ATTENTION_FROM_SCRATCH.PY`](./SELF_ATTENTION_FROM_SCRATCH.PY) | Scaled dot-product self-attention implemented from first principles         |
| [`ROPE.PY`](./ROPE.PY)                                               | Rotary Positional Embeddings (RoPE)                                         |
| [`ROPE_MLA.ipynb`](./ROPE_MLA.ipynb)                                 | Exploration of Rotary Positional Embeddings and Multi-Head Latent Attention |

## Vision-Language Models

| Implementation                                               | Description                                                                              |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| [`VLM_clip_style_nanovlm/`](./VLM_clip_style_nanovlm/)       | CLIP-style vision-language representation learning                                       |
| [`VLM_paligema_from_scratch/`](./VLM_paligema_from_scratch/) | PaLiGemma-style vision-language architecture implemented from its constituent components |

## World Models

| Implementation                                                                                     | Description                                                                |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [`WorldModel_PONGGAME_NextFramePrediction.ipynb`](./WorldModel_PONGGAME_NextFramePrediction.ipynb) | Predictive visual modelling of Pong dynamics through next-frame prediction |

The world-model experiment explores whether a model can learn useful representations of an environment by predicting its future visual states from previous observations.

---

# Some CV Work I did during undergraduate studies before pivoting to LLMs/VLMs/WorldModels

In addition to foundation-model implementations, I have worked on applied computer vision and machine learning systems.

### [Football Match Analysis](https://github.com/MuhammadZakiAhmad/FootBallAnalysisCVProject)

Object detection, multi-object tracking, team assignment using K-Means clustering, and ball-possession analysis from football match footage. Uses YOLOv8 and ByteTrack.

### [Virtual Try-On / Digital Mannequin](https://github.com/MuhammadZakiAhmad/DigitalMannequinForOnlineShops)

Exploration of 3D human reconstruction and virtual apparel visualization using PIFuHD and deep learning-based human modelling techniques.

### [AI Physiotherapy Trainer](https://github.com/MuhammadZakiAhmad/AITrainer-CV-Application-)

Real-time human pose estimation for rehabilitation exercise monitoring, repetition counting, and feedback.

### [Automatic Number Plate Recognition](https://github.com/MuhammadZakiAhmad/ANPRUsingYOLOv8)

Computer vision pipeline combining vehicle detection, license-plate localization, object tracking, and OCR.

### [Human Emotion Detection](https://github.com/MuhammadZakiAhmad/HumanEmotionDetection)

Image classification on FER-2013 for recognition of seven facial expressions.

### [Chest Cancer Classification](https://github.com/MuhammadZakiAhmad/EndToEndChestCancerClassificationUsingMlflowAndDVC)

End-to-end machine learning pipeline incorporating data versioning, experiment tracking, model development, and deployment.

---

# Research & Development Experience

My research and engineering experience spans foundation models, agentic AI, multimodal systems, computer vision, and machine learning.

### NAMETA Labs

**AI R&D Engineer · 2023 – Present**

Research and development involving:

* Foundation models and Transformer architectures
* LLM training, adaptation, and evaluation
* Agentic AI and multi-agent systems
* Multimodal AI and Vision-Language Models
* Retrieval-Augmented Generation and knowledge representation
* Reinforcement learning for agentic systems
* Model distillation and parameter-efficient fine-tuning
* Computer vision and applied machine learning

### ADDO AI

**Data Engineer (Data & AI) · 2024 – Present**

Development of enterprise data and AI systems, including data platforms and multi-agent Text-to-SQL pipelines involving schema linking, retrieval, SQL generation, and validation.

### NAECO BLUE GmbH

**Data Scientist (R&D) · 2023 – 2024**

Research and development in energy forecasting using Transformer-based architectures, LSTMs, ARIMA/SARIMAX, and XGBoost, including investigation of snowfall-related effects on forecasting across Europe.

### PIEAS Data Science Lab

**Researcher · 2023 – 2024**

Research involving 3D human reconstruction, virtual try-on, object detection, segmentation, multi-object tracking, and human movement analysis.

---

# Education

**Bachelor of Computer and Information Sciences**
Pakistan Institute of Engineering and Applied Sciences (PIEAS), Islamabad

**CGPA: 3.51 / 4.00**
**Top Student in AI**

2020 – 2024

---

# Technical Background

**Programming**
Python · SQL

**Deep Learning & Machine Learning**
PyTorch · TensorFlow · Hugging Face · scikit-learn · OpenCV

**LLM & Agentic AI**
Transformers · LangChain · LangGraph · OpenAI Agents SDK

**Data Engineering**
Apache Spark · Apache Kafka · Apache Airflow · Databricks · Trino

**Data Platforms**
Snowflake · PostgreSQL · Oracle · SQL Server · ClickHouse · Apache Iceberg · Delta Lake

**Cloud**
AWS · GCP · Azure · Microsoft Fabric

---

# Research Philosophy

I am interested in understanding modern AI systems beyond their use as high-level software components.

This motivates the first-principles work in this repository: reconstructing architectures from their fundamental components, studying mechanisms such as attention and positional representations, and experimenting with multimodal and predictive models.

The broader objective is to connect **theoretical understanding, implementation, and empirical experimentation** when studying modern AI systems.
