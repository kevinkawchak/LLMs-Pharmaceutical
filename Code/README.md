# Code

**LLM, AI, and Quantum ML Research Notebooks and Scripts**

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.13273141-blue)](https://doi.org/10.5281/zenodo.13273141)

## Overview

This directory contains 2,235 files including 1,446 Jupyter notebooks, 35 Python scripts, and supporting resources organized across 28 research directories. Work spans LLM-driven drug discovery, clinical trial simulation, and quantum machine learning.

| Metric | Value |
|---|---|
| Total Files | 2,235 |
| Jupyter Notebooks | 1,446 |
| Python Scripts | 35 |
| Research Directories | 28 |
| Directory Size | 576 MB |

## Directory Index

### LLM and AI Research (Newer)

| Directory | Files | Notebooks | Description |
|---|---|---|---|
| `Digital_Twin_PDAC/` | 148 | 10 | PDAC digital twin clinical trial proposals — 7 AI model combinations |
| `Drug Discovery/` | 290 | 46 | 14 subdirectories: Agentic-LLM, Multi-LLM, Quad-LLM, ProtBert, ProtGPT2, RAG, and more |
| `Hugging Face/` | 27 | 15 | Llama-3-8B fine-tuning, 32 Hugging Face pipelines, re-trained models, text-to-image |
| `LangChain/` | 17 | 9 | Agent Supervisor, Code Assistant, RAPTOR with GPT-4o evaluations |
| `Generative AI Live/` | 15 | 6 | Live coding demos: RAG, RAPTOR, Agent, fine-tuning on biochemistry dataset |
| `Groq/` | 3 | 1 | GroqCloud inference benchmarks: gemma-7b-it, mixtral-8x7b, llama3-8b, llama3-70b |
| `Open WebUI/` | 3 | 0 | Ollama/Docker GenAI deployment studies with user satisfaction data |
| `Apple/` | 23 | — | LLM Farm demos for MacBook Pro, iPad Pro, iPhone 15 Pro |

### Programming Tutorials

| Directory | Files | Description |
|---|---|---|
| `Python/` | 43 | 34 tutorial scripts (Classes, Inheritance, Multithreading, Sockets, Databases, XML, Recursion, Logging) + network client |
| `C++/` | 47 | C++ tutorial source files |

### Quantum Machine Learning (Historical)

| Directory | Files | Notebooks | Description |
|---|---|---|---|
| `PennyLane/` | 564 | 488 | Algorithm prototyping, benchmarking, data-reuploading, quantum TL, quanvolutional networks, qutrits/qudits |
| `Qiskit/` | 27 | 18 | Quantum programming, effective dimension, device benchmarking |
| `All PennyLane QML Demos/` | 30 | 26 | PennyLane framework demonstrations |
| `All Qiskit ML Demos/` | 16 | 13 | Qiskit ML framework demonstrations |
| `All Qiskit, PennyLane QML Nov 23/` | 56 | 54 | Combined PennyLane/Qiskit notebooks |
| `Efficiency Metrics for Parallel QML Algorithms/` | 190 | — | 9 subdirectories of QML efficiency studies |
| `Parallel Quantum Algorithms torch.nn Seq, Mod/` | 64 | — | Sequential and modular parallel quantum algorithms |
| `PyTorch, Keras, PL Parallel Quantum Algorithms/` | 125 | — | Cross-framework parallel quantum comparisons |
| `QML Parameters for Breakthrough Parallel Algorithms/` | 170 | — | Parameter optimization studies |
| `Quantum Parallel Architectures Progression/` | 171 | — | Architecture progression: 4Q to 320 effective qubits |
| `Qiskit, PennyLane Parallel Algorithms/` | 19 | — | Combined framework parallel algorithms |
| `Tensor Network vs FC Controllability/` | 71 | — | Hyperparameter studies: batch size, epochs, LR, weight decay |
| `Tensor Network vs FC Explainability/` | 59 | — | Explainability comparison datasets |
| `Tensor Network vs Fully Connected Layer/` | 38 | — | Parameter studies and triplicates |
| `Tensor Networks for Generative AI/` | 12 | — | Generative AI tensor network experiments |
| `Cirq/` | 5 | — | Google Cirq quantum computing |

## Drug Discovery Subdirectories

```
Drug Discovery/
├── Agentic-LLM/     # 4 notebooks  — Agentic LLM drug discovery workflows
│   ├── Images/
│   └── Notebooks/
├── Multi-LLM/        # 15 notebooks — Multi-model comparisons, meta-analyses, reports
│   ├── Images/
│   ├── Notebooks/
│   ├── Reports/
│   └── Meta-Analyses/
├── Quad-LLM/         # 14 notebooks — Four-model evaluation pipelines
│   ├── Images/
│   └── Notebooks/
├── ProtBert/          # 1 notebook   — Protein language model experiments
├── ProtGPT2/          # 2 notebooks  — Protein generation models
├── Meta-Llama-3/      # 6 notebooks  — Llama-3 fine-tuning and inference
├── Llama-3 RAG/       # 2 notebooks  — Retrieval-augmented generation
├── LLM/               # LLM approach documentation
├── LLM-RAG/           # Drug synthesis RAG
├── LMM/               # Large multimodal models
├── XLLM/              # Precision medicine
├── pLDM/              # 2 notebooks  — Protein latent diffusion
└── iPhone 15 Pro/     # On-device inference
```

## Digital Twin PDAC Notebooks

```
Digital_Twin_PDAC/Notebooks/
├── Python_01_RP01.ipynb    (2.7 MB) — Research proposal report 1
├── Python_02_RP02.ipynb    (2.9 MB) — Research proposal report 2
├── Python_03_RP03.ipynb    (1.3 MB) — Research proposal report 3
├── Python_04_RP04.ipynb    (1.0 MB) — Research proposal report 4
├── Python_05_RP05.ipynb    (1.4 MB) — Research proposal report 5
├── Python_06_RP06.ipynb    (5.4 MB) — Extended proposal analysis
├── Python_07_Pro5Viz.ipynb (2.2 MB) — 5-proposal visualizations
├── Python_08_Pro5Tab.ipynb  (36 KB) — 5-proposal tabular data
├── Python_09_ProOps4.ipynb (1.5 MB) — Opus 4 Extended proposal
└── Python_10_ProSon4.ipynb (1.7 MB) — Sonnet 4 Extended proposal
```

## License

[Apache License 2.0](LICENSE.md)
