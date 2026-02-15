# Contributing to LLMs-Pharmaceutical

Thank you for your interest in contributing to this project. The following guidelines describe what we accept and how to contribute.

## What We Accept

- **Jupyter notebooks** demonstrating LLM applications in pharmaceutical research, clinical trials, or drug discovery
- **Manuscript summaries** with Zenodo or journal DOI citations
- **Bug reports** for broken links, incorrect citations, or documentation errors
- **Documentation improvements** including README updates and research area descriptions

## Requirements

- All notebook contributions must include a clear description of the LLM(s) or ML framework(s) used
- Citation information (DOI or preprint link) is required for any referenced publication
- Notebooks should be executable in Google Colab or a standard Jupyter environment
- Code should include inline comments explaining methodology

## Development Workflow

1. Fork the repository
2. Create a feature branch from `main`
3. Add or update files in the appropriate directory (`Code/`, `Manuscripts/`, or `R&D/`)
4. Ensure `ruff check .` and `ruff format --check .` pass (CI runs on Python 3.10, 3.11, 3.12)
5. Open a pull request with a description of the contribution

## Code Standards

- **Python**: Checked with [ruff](https://docs.astral.sh/ruff/) (configuration in `ruff.toml`)
- **Notebooks**: Should include markdown cells explaining each step
- **File naming**: Follow the existing directory naming conventions

## Data and Citation

- Do not commit patient-level or personally identifiable health data
- Reference all external datasets by DOI or URL
- Follow Apache 2.0 license terms for code contributions and CC BY 4.0 for manuscript content

## Questions

Open a [GitHub Issue](https://github.com/kevinkawchak/LLMs-Pharmaceutical/issues) or see `SUPPORT.md` for additional help.
