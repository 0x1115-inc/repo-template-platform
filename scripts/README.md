# Scripts

## Purpose

This directory contains operational and automation scripts.

---

# Scope

Scripts here should support:

- Local development bootstrap
- Environment setup
- Deployment automation
- Maintenance tasks
- Operational tooling

---

# Principles

## Idempotency

Scripts should be safe to execute multiple times whenever possible.

---

## Explicitness

Avoid hidden side effects.

Scripts should clearly communicate:

- Inputs
- Outputs
- Required dependencies

---

# Example Structure

```text
scripts/
├── bootstrap/
├── deployment/
├── maintenance/
└── utilities/
```

---

# Example Commands

```bash
./scripts/bootstrap/setup-local.sh

./scripts/deployment/deploy-dev.sh
```