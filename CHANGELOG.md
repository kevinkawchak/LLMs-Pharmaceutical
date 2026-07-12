# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.2.0] - 2026-02-15

### Added
- GitHub Standards: `CHANGELOG.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md`, `CITATION.cff`
- CI pipeline (`.github/workflows/ci.yml`) with ruff lint-and-format across Python 3.10, 3.11, 3.12
- Linter configuration (`ruff.toml`) excluding research notebooks and tutorial scripts
- `.gitignore` for Python, Jupyter, and OS artifacts
- GitHub issue templates (`bug_report.md`, `feature_request.md`) and pull request template
- Detailed `Code/README.md` with full repository structure, notebook counts, and research area index
- Updated `R&D/README.md` with document catalog and topic index
- Prominent link to **LLM Papers: Cancer Drug & Oncology Trials** collection on main README
- @kevinkawchak added Oncology Trial PI LLM Adoption Guide.pdf to main on 2026-06-25.

### Updated
- Main `README.md` restructured with version/license badges, repository structure diagram, research area summaries, and manuscript highlights
- Emphasis shifted to newer LLM-based studies (Digital Twin PDAC, Drug Discovery, clinical trial simulations) with condensed quantum ML sections
- `Manuscripts/` section elevated with publication timeline and DOI links
- `Code/README.md` replaced minimal header with comprehensive directory guide
- @kevinkawchak removed Daraxonrasib Efficient LLM Trial Simulations.pdf and Physical AI Oncology Trial Competition Proposal.pdf from LLMs-Pharmaceutical/tree/main/Guidance; and modified Guidance/README.md on 2026-07-12.

### Notes
- Version numbering continues from the implicit v4.1 state of the repository (801 MB, 2,300+ files, 1,446 notebooks, 30+ publications)
- No existing code or manuscript files were modified; changes are limited to documentation and CI infrastructure
- @kevinkawchak updated DOI image badges in main/Manuscripts to fix mobile viewing issues on 2026-04-26
- @kevinkawchak updated LLM-based Code directories to fix DOI badge issues and other aesthetics issues on 2026-04-26

## [4.1.0] - 2026-02-02

### Added
- `Scaling Oncology LLM Generated Code Jan 2026.pdf` — study on scaling LLM code generation for oncology
- `Daraxonrasib Efficient LLM Trial Simulations.pdf` — efficient LLM trial simulation methodology
- `LaTeX LLM Oncology Table Prompting Guide.pdf` — LaTeX table prompting guide for oncology data

### Updated
- Main `README.md` updated with new project description and DOI links

## [4.0.0] - 2025-12-22

### Added
- `Code/Digital_Twin_PDAC/` — 10-notebook pipeline for pancreatic ductal adenocarcinoma digital twin clinical trial proposals using 7 AI model combinations
- `Code/Drug Discovery/Agentic-LLM/` — agentic LLM workflows for drug discovery
- `Code/Drug Discovery/Multi-LLM/` — multi-LLM comparison notebooks with meta-analyses and reports
- `Code/Drug Discovery/Quad-LLM/` — quad-LLM evaluation notebooks

### Updated
- `Manuscripts/README.md` expanded with 2025 publications covering PDAC digital twins, glioblastoma drug synergy ML, clinical trial LLM efficiency, and 100K patient in silico trials

## [3.0.0] - 2024-12-23

### Added
- `Code/Drug Discovery/` directory — 14 subdirectories covering LLM, LLM-RAG, LMM, ProtBert, ProtGPT2, and multi-model drug discovery approaches
- `Code/Hugging Face/` — Llama-3-8B-Instruct fine-tuning, 32-pipeline benchmark, re-trained models, text-to-image GenAI
- `Code/LangChain/` — Agent Supervisor, Code Assistant, and RAPTOR notebooks with GPT-4o evaluations
- `Code/Generative AI Live/` — live coding demos for RAG, RAPTOR, Agent, and fine-tuning
- `Code/Open WebUI/` — Ollama/Docker GenAI deployment studies
- `Code/Groq/` — GroqCloud inference benchmarks for 4 models

### Updated
- `Manuscripts/README.md` expanded with 2024 publications on spectrometric analysis, paclitaxel biosynthesis, mAb bioprocess engineering, and cancer vs. conversational AI

## [2.0.0] - 2024-08-12

### Added
- `Code/Tensor Network vs FC Controllability/` — hyperparameter studies comparing tensor networks and fully connected layers
- `Code/Tensor Network vs FC Explainability/` — explainability comparison datasets
- `Code/Tensor Network vs Fully Connected Layer/` — parameter studies and triplicates
- `Code/Tensor Networks for Generative AI/` — generative AI tensor network experiments

### Updated
- Manuscripts expanded with spectrometric determination studies and LMM chemical research publications

## [1.0.0] - 2023-11-01

### Added
- `Code/PennyLane/` — 488 quantum ML notebooks covering algorithm prototyping, benchmarking, data-reuploading, quantum transfer learning, quanvolutional networks, and qutrits/qudits
- `Code/Qiskit/` — 18 notebooks with quantum programming tutorials and device benchmarking
- `Code/All PennyLane QML Demos/` — 26 PennyLane demo notebooks
- `Code/All Qiskit ML Demos/` — 13 Qiskit ML demo notebooks
- `Code/All Qiskit, PennyLane QML Nov 23/` — 54 combined framework notebooks
- `Code/Efficiency Metrics for Parallel QML Algorithms/` — 9 subdirectories of QML efficiency studies
- `Code/Parallel Quantum Algorithms torch.nn Seq, Mod/` — sequential and modular parallel quantum algorithms
- `Code/PyTorch, Keras, PL Parallel Quantum Algorithms/` — cross-framework parallel quantum algorithm comparisons
- `Code/QML Parameters for Breakthrough Parallel Algorithms/` — parameter optimization studies
- `Code/Quantum Parallel Architectures Progression/` — architecture progression from 4Q to 320 effective qubits
- `Code/Python/` — 34 Python tutorial scripts and network client
- `Code/C++/` — C++ tutorial source files
- `Code/Apple/` — LLM Farm demos for MacBook Pro, iPad Pro, iPhone 15 Pro
- `R&D/` — 70 research and development markdown documents covering QML algorithms, medical applications, and industry analysis
- `Manuscripts/README.md` — initial research papers index
- Apache License 2.0 (`LICENSE.md`)
