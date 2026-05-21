# Documentation

## Purpose
This directory contains system-level documentation.

Unlike service-specific documentation, documents here describe:
- Overall architecture
- Cross-service interactions
- Deployment topology
- Governance decisions
- Operational processes
- Knowledge base for platform-wide concerns

## Structure
```text
docs/
├── architecture/        # System architecture diagrams and explanations
├── adrs/                # Architectural Decision Records
├── kb/                  # Knowledge base articles and best practices
├── runbooks/            # Operational runbooks and incident response guides
├── integration/         # Integration guides for new team members
```

## Principles
### System Perspective
Documentation here should explain how the platform works as a whole.

### Avoid Duplication
Do not duplicate detailed service implementation documents from service repositories. Instead, reference them when appropriate.

## Architecture Decision Records
Important architectural changes should be documented under `docs/adrs/`.

## Example Topics
- Service interation
- Authentication flow
- Deployment model
- Observability architecture
- Disaster recovery
- Scaling strategy