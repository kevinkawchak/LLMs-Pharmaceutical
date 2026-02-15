# Security Policy

## Scope

This repository contains research notebooks, manuscripts, and documentation for LLM applications in pharmaceutical development and oncology clinical trials. It does not include deployed services, APIs, or patient-facing software.

## Reporting a Vulnerability

If you discover a security issue (e.g., exposed credentials, data leakage in a notebook, or a dependency vulnerability), please report it confidentially:

- **Email**: kevink@chemicalqdevice.com
- **Subject line**: `[SECURITY] LLMs-Pharmaceutical — <brief description>`

## Response Timeline

| Action | Target |
|---|---|
| Acknowledgment | 7 days |
| Fix or mitigation | 30 days |

## Supported Versions

Security reports are accepted for the latest `main` branch only.

## Researcher Responsibilities

- Do not commit protected health information (PHI), personally identifiable information (PII), or API keys
- Notebook outputs should be reviewed before committing to ensure no sensitive data is included
- LLM-generated code executed on patient data may require FDA approval; see individual study disclosures

## Dependencies

This repository does not maintain a centralized `requirements.txt` for all notebooks. Individual notebooks may reference third-party packages (PyTorch, PennyLane, LangChain, etc.) whose security is managed upstream by their respective maintainers.
