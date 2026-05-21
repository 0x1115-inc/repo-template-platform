# Environments

## Purpose

This directory defines environment-specific configuration and deployment composition.

---

# Supported Environments

- local
- dev
- staging
- production

---

# Principles

## Environment Isolation

Each environment should:

- Have isolated configuration
- Use explicit variables
- Avoid hidden dependencies

---

## Immutable Deployment

Deployment configuration should be reproducible and version-controlled.

---

# Example Structure

```text
environments/
├── local/
│   ├── .env.example
│   └── overrides/
├── dev/
├── staging/
└── production/
```

---

# Important Rules

- Never commit secrets
- Use secret management systems
- Keep environment naming consistent
- Avoid environment-specific application logic