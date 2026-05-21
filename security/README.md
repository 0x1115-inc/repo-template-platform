# Security

## Purpose

This directory contains platform-level security configuration and guidance.

---

# Scope

- Secret management templates
- Access policies
- TLS configuration
- Security standards
- Compliance references

---

# Example Structure

```text
security/
├── secrets-template/
├── access-policy/
├── tls/
└── compliance/
```

---

# Principles

## Least Privilege

Access should be granted only as necessary.

---

## Secret Separation

Secrets must never be committed directly into repositories.

---

## Traceability

Security-sensitive changes should be auditable.

---

# Recommended Practices

- Use external secret managers
- Rotate credentials regularly
- Separate runtime and deployment credentials
- Use RBAC consistently