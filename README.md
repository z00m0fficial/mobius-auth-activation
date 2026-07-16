# Mobius Authentication Activation

This repository contains controlled, read-only integration verification workflows for Mobius Technologies.

## Current verification

- Name.com API authentication test
- No DNS records are created, edited, or deleted
- No production deployment is performed
- Secrets remain stored in GitHub Actions encrypted repository secrets

## Organizational Intelligence Alignment

Authentication and connector verification establish identity and connectivity; they do not automatically grant permission for the Organizational Intelligence Engine™ to read, learn from, modify, or publish organizational data.

All future workflows must preserve tenant isolation, role-based authorization, approval boundaries, audit evidence, and secret confidentiality. Mobius may retain connector health and authorization metadata, but it must never store raw credentials in Brain Core™, logs, prompts, or documentation.

See `docs/ORGANIZATIONAL_INTELLIGENCE_AUTH_ALIGNMENT_V1.md`.