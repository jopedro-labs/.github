# Contributing Guidelines

Thank you for your interest in contributing to a **jopedro-labs** project!

Each repository may define its own specific contributing guidelines. This document covers the baseline standards that apply across all projects in this organization.

## General Principles

- Keep contributions focused and atomic — one concern per Pull Request.
- Every PR must have a clear title and description explaining *why* the change is needed.
- Never commit credentials, API keys, tokens, or personal data of any kind.
- Use mock data in tests — unit tests must not call live external endpoints.

## Quality Gates

All contributions must pass the project's local quality checks before opening a Pull Request. Refer to the individual repository's `CONTRIBUTING.md` or `Makefile` for the exact commands. CI will enforce all gates automatically — PRs that fail any gate will not be merged.

## Pull Request Workflow

1. Fork the repository and create a feature branch from `main`:
   ```bash
   git checkout -b feat/your-feature
   ```
2. Make your changes and ensure all quality gates pass locally.
3. Open a Pull Request against `main`.
4. Address any review feedback before the PR is merged.
5. Squash fixup commits before requesting a final review.

## Code Licensing

By submitting a Pull Request or contributing code to any repository in this organization, you agree that:

1. Your contribution is licensed under the repository's existing license (typically **MIT**).
2. You grant the project maintainer a perpetual, irrevocable license to use, modify, and distribute your code.
3. You warrant that you hold the necessary rights to submit the code free of third-party IP encumbrances.

## Code of Conduct

All contributors are expected to follow the organization's [Code of Conduct](CODE_OF_CONDUCT.md).
