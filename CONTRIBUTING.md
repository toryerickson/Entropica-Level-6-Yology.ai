# Contributing to EFM Codex

## Overview

The Entropica Forensic Model (EFM) Codex is a proprietary technical specification maintained by Entropica SPC's Yology Research Division.

## Reporting Issues

If you discover errors, inconsistencies, or have suggestions:

1. **Technical Errors**: Open an issue with the document name, section, and specific error
2. **Architectural Questions**: Open a discussion thread
3. **Security Concerns**: Contact security@entropica.ai directly

## Document Standards

All contributions must:

- Use consistent terminology (see `efm_canonical_terminology.pdf`)
- Include test cases for new specifications
- Reference affected properties (P1–P8)
- Update CHANGELOG.md

## Pull Request Process

1. Fork the repository
2. Create a feature branch
3. Make changes in LaTeX source
4. Compile and verify PDFs
5. Update version numbers
6. Submit PR with description

## Testing Requirements

New specifications must include:

- Unit test definitions
- Integration test scenarios (if cross-component)
- Invariant specifications
- Formal proof sketches (for safety-critical changes)

## License

This is proprietary software. See LICENSE for terms.

---

*Yology Research Division — Entropica SPC*
